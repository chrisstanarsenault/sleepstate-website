<template>
  <section
    id="listen"
    class="flex flex-col justify-center items-center text-white space-y-10 bg-gray-900 py-8 md:py-16"
  >
    <div class="text-center space-y-4">
      <h3 class="text-3xl md:text-5xl">
        Listen to the new single
      </h3>

      <h2 class="text-5xl md:text-7xl">
        How Am I
      </h2>
    </div>

    <div class="w-full hidden md:flex justify-center">
      <iframe
        style="border-radius:12px"
        src="https://open.spotify.com/embed/track/1wptdPzZChLBGUcrzh9sTx?utm_source=generator&theme=0"
        width="100%"
        height="352"
        frameBorder="0"
        allowfullscreen="false"
        allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
        loading="lazy"
        class="w-1/2"
      />
    </div>

    <div class="flex md:hidden justify-center">
      <iframe
        style="border-radius:12px"
        src="https://open.spotify.com/embed/track/1wptdPzZChLBGUcrzh9sTx?utm_source=generator"
        width="100%"
        height="152"
        frameBorder="0"
        allowfullscreen="true"
        allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
        loading="lazy"
      />
    </div>
  </section>
</template>
