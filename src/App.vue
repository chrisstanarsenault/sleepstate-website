<template>
  <div class="bg-black space-y-4">
    <Landing />
    <Video />
    <Listen />
    <Albums />
    <MusicVideos />
    <Shows />
  </div>
</template>

<script setup lang="ts">
import Landing from '#pages/landing.vue'
import Video from '#pages/video.vue'
import Listen from '#pages/listen.vue'
import Albums from '#pages/albums.vue'
import MusicVideos from '#pages/music-videos.vue'
import Shows from '#pages/shows.vue'
</script>
