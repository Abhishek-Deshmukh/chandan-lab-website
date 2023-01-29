
<script setup lang="ts">
import { isDark, toggleDark } from '~/composables'
const { t, availableLocales, locale } = useI18n()

const scrollPosition = ref(0)
const basic_classes = 'mx-auto flex flex-wrap p-2 flex-col md:flex-row items-start lg:rounded-xl md:rounded-lg transition-all duration-500 text-gray-500 <md:text-white'

function updateScroll(this: any) {
  scrollPosition.value = window.scrollY
}

onMounted (() => {
  window.addEventListener('scroll', updateScroll)
})

const navDivClasses = computed(() => {
  if (scrollPosition.value < 100)
    return basic_classes

  else
    return `${basic_classes} bg-white dark:bg-black shadow-xl <md:text-gray-500`
})
</script>

<template>
  <div class="w-screen items-center fixed">
    <header class="lg:mt-5 md:mt-3 lg:mx-auto md:mx-auto container lg:max-w-13/14 md:max-w-19/20 sm:max-w-14/14 sm:m-0">
      <div
        :class="navDivClasses"
      >
        <nav
          class="ml-auto md:mr-auto flex flex-initial flex-wrap items-start text-start uppercase font-sans text-3xl justify-start"
        >
          <router-link class="hover:bg-gray-200 rounded-md px-2 mt-1 xl:mr-10 transition-all duration-100 hover:text-4xl <md:(text-2xl)" to="/">
            Home
          </router-link>
          <router-link class="hover:bg-gray-200 rounded-md px-4 mt-1 transition-all duration-100 hover:text-4xl <md:(text-2xl ml-auto pr-6)" to="/research">
            Research
          </router-link>

          <span class="title-font font-medium items-center lg:mb-1 @md:mb-1 <md:(w-screen px-auto) sm:mb-0">
            <router-link
              class="mt-1 text-4xl hover:underline xl:px-40 md:(text-3xl) <md:(text-3xl)"
              draggable="false"
              to="/"
            >CG LAB</router-link>
          </span>

          <router-link class="hover:bg-gray-200 rounded-md px-4 mt-1 transition-all duration-100 hover:text-4xl <md:text-2xl" to="/people">
            People
          </router-link>
          <router-link
            class="hover:bg-gray-200 rounded-md px-2 mt-1 xl:ml-10 transition-all duration-100 hover:text-4xl <md:(text-2xl ml-auto pr-6)"
            to="/publications"
          >
            Publications
          </router-link>
        </nav>
        <span class="border-0 py-1 px-3 mt-4 md:mt-0 inline-flex items-center w-4 h-4 ml-1" />

        <button
          class="icon-btn text-gray-500"
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
