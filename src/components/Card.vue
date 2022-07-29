<script setup lang="ts">
const props = defineProps<{ name: string; description: string; img: string; position: string }>()
</script>

<template>
  <div class="h-120">
    <div class="bg-gray-200 dark:bg-gray-800 h-110 mt-5 mx-8 rounded flex flex-col items-center p-6 text-center">
      <img
        class="w-100% h-50 rounded"
        :src="props.img"
        :alt="props.name"
      >
      <p class="text-xl mt-4 uppercase font-medium font-sans">
        {{ props.name }}
      </p>
      <p class="font-sans">
        {{ props.position }}
      </p>
      <p
        class="mt-1"
      >
        {{ props.description }}
      </p>
    </div>
  </div>
</template>
