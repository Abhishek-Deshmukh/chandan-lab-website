<script setup lang="ts">
// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: 'C G Lab NISER - Defeating Pain',
  meta: [
    { name: 'description', content: 'Defeating Pain' },
    { name: 'keywords', content: 'Pain, NISER, research, biology, defeating pain' },
  ],
})
</script>

<template>
  <router-view />
</template>
