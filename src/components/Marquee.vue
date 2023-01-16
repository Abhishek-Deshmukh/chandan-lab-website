<template>
  <div class="marquee">
    <div ref="content" class="marquee-content pt-7" :style="{ transform: 'translateX(' + translateX + 'px)' }">
      <img v-for="img in images" :key="img" :src="img">
    </div>
  </div>
</template>

<script>
export default {
  props: {
    imgUrls: {
      type: Array,
      required: true,
    },
  },
  data() {
    return {
      translateX: 0,
      intervalId: null,
      images: [],
    }
  },
  mounted() {
    this.images = this.imgUrls
    this.startAnimation()
  },
  beforeUnmount() {
    this.stopAnimation()
  },
  methods: {

    startAnimation() {
      let imageWidths = 0
      let currentImageIndex = 0
      this.$refs.content.childNodes.forEach((img) => {
        imageWidths += img.clientWidth
      })
      let isPaused = false
      this.intervalId = setInterval(() => {
        currentImageIndex = Math.abs((this.translateX / this.$el.clientWidth) % this.$refs.content.childNodes.length)
        if (!isPaused) {
          if (this.translateX <= -7000)
            this.translateX = 0

          else
            this.translateX -= this.$el.clientWidth
        }
        if (imageWidths + this.translateX <= this.$el.clientWidth)
          this.translateX = -imageWidths + this.$el.clientWidth

        if (currentImageIndex !== Math.abs((this.translateX / this.$el.clientWidth) % this.$refs.content.childNodes.length)) {
          isPaused = true
          setTimeout(() => {
            isPaused = false
          }, 2700)
        }
      }, 100)
    },

    stopAnimation() {
      clearInterval(this.intervalId)
    },
  },
}
</script>

<style>
.marquee {
  overflow: hidden;
  position: relative;
}

.marquee-content {
  display: flex;
  white-space: nowrap;
}

.marquee-content img {
  height: 100%;
  width: auto;
}
</style>
