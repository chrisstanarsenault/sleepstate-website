<template>
  <div class="w-full h-screen bg-[url('./assets/band3.jpg')] bg-cover bg-center text-white">
    <Header />

    <RouterView />
  </div>
</template>

<script setup lang="ts">
import Header from '#components/header/header.vue'
</script>
