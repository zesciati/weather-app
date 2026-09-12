<script setup lang="ts"></script>

<template>
  <nav class="flex justify-between">
    <img src="/images/logo.svg" alt="logo-weather-now" class="w-35" />
    <div class="flex bg-neutral-600 px-2 py-1 gap-2 rounded-lg">
      <img src="/images/icon-units.svg" alt="icon-units" class="w-4" />
      <p class="text-white">Units</p>
      <img src="/images/icon-dropdown.svg" alt="icon-units" class="w-3" />
    </div>
  </nav>


  <div class="flex justify-center items-center text-center my-10">
    <h1 class="text-white text-6xl font-bricolage">
      How's the sky looking today?
    </h1>
  </div>

  <section class="space-y-2">
    <div>
      <img src="/images/icon-search.svg" alt="">
      <input type="search" name="" id="" placeholder="Search for a place" class="w-full bg-neutral-600">
    </div>
    <button type="submit" aria-label="search" class="bg-blue-500 w-full text-white">Search</button>
  </section>
</template>
