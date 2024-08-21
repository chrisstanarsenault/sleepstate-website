<template>
  <header class="absolute top-0 w-full flex justify-between items-center px-6 md:px-20 py-4 md:py-10 bg-black">
    <h1 class="text-xl md:text-4xl text-white">
      Sleepstate
    </h1>

    <div class="hidden md:block">
      <nav class="text-lg space-x-4">
        <a href="#landing">
          Home
        </a>

        <a href="#listen">
          Listen
        </a>

        <a href="#albums">
          Albums
        </a>

        <a href="#music-videos">
          Videos
        </a>
      </nav>
    </div>

    <button @click="toggleMenu">
      <Hamburger class="block md:hidden w-8 h-8 text-white" />
    </button>
  </header>
</template>

<script setup lang="ts">
import Hamburger from '#components/icons/hamburger.vue'

const emit = defineEmits(['toggleMenu'])

const toggleMenu = () => {
  emit('toggleMenu')
}
</script>
