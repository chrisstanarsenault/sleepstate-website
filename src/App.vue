<template>
  <div
    class="bg-black space-y-4"
    :class="isMenuOpen ? 'fixed w-full h-full' : ''"
  >
    <Landing @toggle-menu="isMenuOpen = !isMenuOpen" />
    <Video />
    <Listen />
    <Albums />
    <MusicVideos />
    <Shows />
    <Footer />
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'
import Landing from '#pages/landing.vue'
import Video from '#pages/video.vue'
import Listen from '#pages/listen.vue'
import Albums from '#pages/albums.vue'
import MusicVideos from '#pages/music-videos.vue'
import Shows from '#pages/shows.vue'
import Footer from '#components/footer/footer.vue'

const isMenuOpen = ref(false)
</script>
