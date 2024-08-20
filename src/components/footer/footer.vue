<template>
  <footer class="bg-black text-white py-10">
    <div class="flex justify-around">
      <p>
        &copy; 2024 Sleepstate
      </p>

      <div class="flex space-x-4">
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
  </footer>
</template>

<script setup lang="ts">
import Header from '#components/header/header.vue'
import Instagram from '#components/icons/instagram.vue'
import Linktree from '#components/icons/linktree.vue'
import Spotify from '#components/icons/spotify.vue'
import Youtube from '#components/icons/youtube.vue'
</script>
