<template>
  <section
    id="albums"
    class="flex flex-col justify-center items-center text-white space-y-10 bg-gray-900 py-8 md:py-16"
  >
    <h3 class="text-3xl md:text-5xl">
      Albums
    </h3>

    <div class="flex flex-col md:flex-row space-y-4 md:space-x-4 items-center md:justify-center px-4 md:px-0">
      <img
        :src="VersionsAlbum"
        alt="Versions Album"
        class="w-full md:w-96 aspect-square object-cover"
      >
      <img
        :src="YouComeBeforeYouAlbum"
        alt="You Come Before You Album"
        class="w-full md:w-96 aspect-square object-cover"
      >
    </div>

    <div class="flex flex-col items-center space-y-4">
      <p class="text-center text-white mt-4 text-2xl">
        Check these out on:
      </p>

      <div class="space-x-4 flex">
        <a
          href="https://open.spotify.com/artist/7m6oY8iyHKC2x8tBpiWDjo?si=8Pa-SjTSTHaN20QMdCM94g"
          target="_blank"
        >
          <Spotify class="w-8 h-8" />
        </a>

        <a
          href="#"
          target="_blank"
        >
          <AppleMusic class="w-8 h-8" />
        </a>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import Spotify from '#components/icons/spotify.vue'
import AppleMusic from '#components/icons/apple-music.vue'

import VersionsAlbum from '#assets/VERSIONS.webp'
import YouComeBeforeYouAlbum from '#assets/YOU-COME-BEFORE-YOU.webp'
</script>
