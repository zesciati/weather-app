<script setup lang="ts"></script>

<template>
  <nav>
    <section class="flex justify-between">
      <img src="/images/logo.svg" alt="logo-weather-now" class="w-35" />
      <div class="flex bg-neutral-600 px-2 py-1 gap-2 rounded-lg">
        <img src="/images/icon-units.svg" alt="icon-units" class="w-4" />
        <p class="text-white">Units</p>
        <img src="/images/icon-dropdown.svg" alt="icon-units" class="w-3" />
      </div>
    </section>

    <section class="flex justify-center items-center text-center my-10">
      <h1 class="text-white text-6xl font-bricolage">
        How's the sky looking today?
      </h1>
    </section>

    <section class="space-y-2">
      <div class="flex bg-neutral-600 py-2.5 px-6 gap-4 rounded-lg">
        <img src="/images/icon-search.svg" alt="icon-search">
        <input type="search" name="" id="" placeholder="Search for a place" class="w-full outline-0">
      </div>
      <button type="submit" aria-label="search" class="bg-blue-500 w-full text-white rounded-lg py-2.5 font-dmsans hover:bg-blue-700 hover:ease-in-out hover:duration-100 cursor-pointer active:scale-98 active:border-2 active:border-blue-500/50">Search</button>
    </section>
  </nav>
</template>
