
<script setup lang="ts">
const props = defineProps<{ title: string; description: string; img: string }>()
</script>

<template>
  <div class="w-100% m-3 bg-gray-200 dark:bg-gray-800 xl:h-xl rounded-xl">
    <div class="xl:flex xl:flex-row">
      <div class="xl:basis-full xl:h-xl xl:pt-10">
        <img :src="img" class="xl:h-100% xl:mx-auto md:mx-auto md:pt-9">
      </div>
      <div class="xl:basis-full xl:pt-8 xl:pr-10 xl:pb-5 md:p-7 p-5">
        <h2 class="text-4xl">
          {{ props.title }}
        </h2>
        <div class="bg-teal-300 w-10 h-2 my-3" />
        <p class="text-xl xl:text-left md:text-center">
          {{ props.description }}
        </p>
      </div>
    </div>
  </div>
</template>
