<template>
  <h2 class="text-4xl underline pt-7 pl-3">
    Gallery
  </h2>

  <div class="grid xl:grid-cols-3 md:grid-cols-2 sm:grid-cols-1">
    <img
      v-for="image in images"
      :key="image"
      :src="image"
      class="p-4 rounded-xl"
    >
  </div>
</template>

<script>
export default {
  data() {
    return {
      images: ['/img/gallery/embo grp 1.jpg',
        '/img/gallery/embo grp 2.jpg',
        '/img/gallery/embo grp 3.jpg',
        '/img/gallery/IMG-20210827-WA0008 - Shamit Kumar.jpg',
        '/img/gallery/IMG-20210827-WA0009 - Shamit Kumar.jpg',
        '/img/gallery/Snapchat-118171004 - Shamit Kumar.jpg',
        '/img/gallery/IMG-20210910-WA0007 - Shamit Kumar.jpg',
        '/img/gallery/IMG-20210910-WA0012 - Shamit Kumar.jpg',
        '/img/gallery/IMG-20211216-WA0020 - Ritesh Dalai.jpg',
        '/img/gallery/IMG20210910115940 - Ram Prasad Sahu.jpg',
        '/img/gallery/IMG20211222163543 - Ram Prasad Sahu.jpg',
        '/img/gallery/Main page Image1 - Rakesh Kumar Majhi.png',
        '/img/gallery/Main page Image3 - Rakesh Kumar Majhi.png',
        '/img/gallery/Main page Image4 - Rakesh Kumar Majhi.png',
        '/img/gallery/Main page Image5 - Rakesh Kumar Majhi.png',
        '/img/gallery/Testis-2 - Rakesh Kumar Majhi.jpg'],
    }
  },
}
</script>
