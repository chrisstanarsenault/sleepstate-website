<template>
  <section class="w-full bg-gray-900 p-10 space-y-32">
    <Listen />

    <div class="h-.05 w-3/4 border-t-2 border-white mx-auto" />

    <Albums />

    <div class="h-.05 w-3/4 border-t-2 border-white mx-auto" />

    <MusicVideos />
  </section>
</template>

<script setup lang="ts">
import Listen from '#components/music/listen.vue'
import Albums from '#components/music/albums.vue'
import MusicVideos from '#components/music/music-videos.vue'
</script>
