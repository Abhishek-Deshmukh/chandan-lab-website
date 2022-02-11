<script setup lang="ts">
import { useUserStore } from '~/stores/user'

const user = useUserStore()
const name = ref(user.savedName)

const router = useRouter()
const go = () => {
  if (name.value)
    router.push(`/hi/${encodeURIComponent(name.value)}`)
}

const { t } = useI18n()
</script>

<template>
  <div class="top-0 left-0 h-screen w-screen z-0 flex bg-gray-300 dark:bg-gray-700">
    <div class="m-auto text-3xl lg:text-6xl md:text-4xl text-black dark:text-white">
      Chandan Ghoswami Lab
    </div>
  </div>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
