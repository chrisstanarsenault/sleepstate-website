<template>
  <section
    id="landing"
    class="relative w-full h-screen text-white"
  >
    <Header />

    <div class="grid grid-cols-12 gap-x-4 h-full">
      <div class="col-span-11 bg-[url('./assets/band3.jpg')] bg-cover bg-center">
        <h2 class="text-8xl">
          We are Sleepstate
        </h2>
      </div>

      <div class="col-span-1 space-y-8 flex flex-col justify-end items-center bg-gray-900 p-4">
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
  </section>
</template>

<script setup lang="ts">
import { ref } from 'vue'

import Header from '#components/header/header.vue'
import Instagram from '#components/icons/instagram.vue'
import Linktree from '#components/icons/linktree.vue'
import Spotify from '#components/icons/spotify.vue'
import Youtube from '#components/icons/youtube.vue'
</script>
