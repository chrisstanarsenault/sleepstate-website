<template>
  <section class="w-full">
    <div class="flex space-x-4 justify-center">
      <img
        :src="VersionsAlbum"
        alt="Versions Album"
        class="w-96 h-96 object-cover"
      >
      <img
        :src="YouComeBeforeYouAlbum"
        alt="You Come Before You Album"
        class="w-96 h-96 object-cover"
      >
    </div>

    <div class="flex flex-col items-center space-y-4">
      <p class="text-center text-white mt-4 text-2xl">
        Check these out on:
      </p>

      <div class="space-x-4 flex">
        <Spotify class="w-8 h-8" />
        <AppleMusic class="w-8 h-8" />
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
