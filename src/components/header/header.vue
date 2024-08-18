<template>
  <header class="w-full flex justify-between px-20 py-10 relative">
    <h1 class="text-2xl text-white">
      Sleepstate
    </h1>

    <div>
      <nav class="text-lg space-x-4">
        <RouterLink to="/">
          Home
        </RouterLink>

        <RouterLink to="/music">
          Music
        </RouterLink>

        <RouterLink to="/shows">
          Shows
        </RouterLink>

        <RouterLink to="/about">
          About
        </RouterLink>
      </nav>
    </div>
  </header>
</template>
