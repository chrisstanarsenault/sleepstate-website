<template>
  <section class="w-full">
    <video
      autoplay
      loop
      muted
      class="w-full h-96 object-cover"
    >
      <source
        :src="Video"
        type="video/mp4"
      >
    </video>
  </section>
</template>

<script setup lang="ts">
import Video from '#assets/bandvid.mp4'
</script>
