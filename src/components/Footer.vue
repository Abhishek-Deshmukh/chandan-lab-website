<script setup lang="ts">
import { isDark, toggleDark } from '~/composables'

const { t, availableLocales, locale } = useI18n()

const toggleLocales = () => {
  // change to some real logic
  const locales = availableLocales
  locale.value = locales[(locales.indexOf(locale.value) + 1) % locales.length]
}
</script>

<template>
  <footer class="container mx-auto flex flex-wrap p-5 flex-col mt-5 md:flex-row items-start rounded-xl bg-gray-700 shadow-xl dark:bg-green-700 text-white">
    Made with ♥ by Abhishek Anil Deshmukh
  </footer>
</template>
