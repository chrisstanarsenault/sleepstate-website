<template>
  <section
    id="landing"
    class="relative w-full h-screen text-white"
  >
    <Header @toggle-menu="handleToggleMenu" />

    <div
      v-if="!isMenuOpen"
      class="md:grid md:grid-cols-12 gap-x-4 h-full"
    >
      <div class="flex flex-col justify-center md:col-span-11 bg-[url('./assets/band3.jpg')] bg-cover bg-center h-full">
        <h2 class="text-3xl md:text-8xl text-center">
          We are Sleepstate
        </h2>

        <div class="absolute bottom-0 left-1/2 -translate-x-1/2 space-x-8 md:hidden flex justify-center p-4">
          <a
            href="#"
            target="_blank"
          >
            <Instagram class="w-6 h-6" />
          </a>

          <a
            href="https://www.linktr.ee/sleepstate"
            target="_blank"
          >
            <Linktree class="w-6 h-6" />
          </a>

          <a
            href="https://open.spotify.com/artist/7m6oY8iyHKC2x8tBpiWDjo?si=8Pa-SjTSTHaN20QMdCM94g"
            target="_blank"
          >
            <Spotify class="w-6 h-6" />
          </a>

          <a
            href="https://www.youtube.com/@wearesleepstate"
            target="_blank"
          >
            <Youtube class="w-6 h-6" />
          </a>
        </div>
      </div>

      <div class="md:col-span-1 space-y-8 hidden md:flex flex-col justify-end items-center bg-gray-900 p-4">
        <a
          href="#"
          target="_blank"
        >
          <Instagram class="w-8 h-8" />
        </a>

        <a
          href="https://www.linktr.ee/sleepstate"
          target="_blank"
        >
          <Linktree class="w-8 h-8" />
        </a>

        <a
          href="https://open.spotify.com/artist/7m6oY8iyHKC2x8tBpiWDjo?si=8Pa-SjTSTHaN20QMdCM94g"
          target="_blank"
        >
          <Spotify class="w-8 h-8" />
        </a>

        <a
          href="https://www.youtube.com/@wearesleepstate"
          target="_blank"
        >
          <Youtube class="w-8 h-8" />
        </a>
      </div>
    </div>

    <div v-else>
      <div class="w-full h-full flex flex-col justify-center items-center space-y-8">
        <a
          href="#landing"
          class="text-2xl"
        >
          Home
        </a>

        <a
          href="#listen"
          class="text-2xl"
        >
          Listen
        </a>

        <a
          href="#albums"
          class="text-2xl"
        >
          Albums
        </a>

        <a
          href="#music-videos"
          class="text-2xl"
        >
          Videos
        </a>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import { ref } from 'vue'

import Header from '#components/header/header.vue'
import Instagram from '#components/icons/instagram.vue'
import Linktree from '#components/icons/linktree.vue'
import Spotify from '#components/icons/spotify.vue'
import Youtube from '#components/icons/youtube.vue'

const emit = defineEmits(['toggle-menu'])

const isMenuOpen = ref(false)

const handleToggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value

  emit('toggle-menu')
}
</script>
