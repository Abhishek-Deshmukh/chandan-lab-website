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
  <footer
    class="container mx-auto flex flex-row p-5 flex-col mt-5 mb-5 md:flex-row items-start lg:rounded-xl md:rounded"
  >
    <div class="basis-full">
      <img src="/img/signature.png" alt="Dr. Chandan Goswami" class="h-20 ml-40 filter invert dark:invert-0">
    </div>
    <div class="basis-full">
      <img src="/img/niser_white_logo.png" alt="NISER logo" class="h-30 ml-60 filter invert dark:invert-0">
    </div>

    <div class="basis-full pt-8">
      Made with ♥ by <a href="https://abhishek-deshmukh.com" class="hover:underline pl-2" target="__blank"> Abhishek Anil Deshmukh</a>
    </div>
  </footer>
</template>
