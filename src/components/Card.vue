<script setup lang="ts">
const props = defineProps<{ name: string; description: string; img: string }>()
</script>

<template>
  <div class="h-140">
    <div class="bg-gray-200 dark:bg-gray-800 h-130 mt-5 mx-8 rounded flex flex-col items-center p-6 text-center">
      <img
        class="w-50 h-50 lg:rounded-4xl md:rounded-xl"
        :src="props.img"
        :alt="props.name"
      >
      <p class="text-xl mt-4 uppercase font-medium">
        Tejas Pravin Rokade
      </p>
      <p
        class="mt-1"
      >
        {{ props.description }}
      </p>
    </div>
  </div>
</template>
