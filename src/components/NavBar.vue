
<script setup lang="ts">
import { isDark, toggleDark } from '~/composables'
const { t, availableLocales, locale } = useI18n()
</script>

<template>
  <div class="w-screen items-center fixed">
    <header class="body-font lg:mt-5 md:mt-3 lg:mx-auto md:mx-auto container lg:max-w-13/14 md:max-w-19/20 sm:max-w-14/14 sm:m-0">
      <div
        class="mx-auto flex flex-wrap p-2 flex-col md:flex-row items-start lg:rounded-xl md:rounded-lg bg-gray-700 shadow-xl dark:bg-green-700"
      >
        <span class="flex title-font font-medium items-center text-black mb-6 md:mb-0">
          <router-link
            class="ml-2 mt-1 text-xl text-white hover:underline"
            draggable="false"
            to="/"
          >CG Lab</router-link>
        </span>
        <nav
          class="ml-auto md:mr-auto flex flex-initial flex-wrap items-start text-start text-lg justify-start text-white"
        >
          <router-link class="hover:bg-gray-500 rounded-md px-2 mt-1" to="/">
            Home
          </router-link>
          <router-link class="hover:bg-gray-500 rounded-md px-2 mt-1" to="/research">
            Research
          </router-link>
          <router-link class="hover:bg-gray-500 rounded-md px-2 mt-1" to="/people">
            People
          </router-link>
          <router-link
            class="hover:bg-gray-500 rounded-md px-2 mt-1"
            to="/publications"
          >
            Publications
          </router-link>
        </nav>
        <span class="border-0 py-1 px-3 mt-4 md:mt-0 inline-flex items-center w-4 h-4 ml-1" />

        <button
          class="icon-btn !outline-none text-light-50"
          :title="t('button.toggle_dark')"
          @click="toggleDark()"
        >
          <carbon-moon v-if="isDark" />
          <carbon-sun v-else />
        </button>
      </div>
    </header>
  </div>
</template>
