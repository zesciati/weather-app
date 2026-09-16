<script setup lang="ts"></script>

<template>
  <div>


    <section
      class="bg-[url(/images/bg-today-small.svg)] resone:rounded-xl sm:bg-[url(/images/bg-today-large.svg)] bg-center bg-no-repeat bg-size-[100%_100vh] flex items-center flex-col p-11 "
    >
      <div class="text-center space-y-2">
        <h1 class="text-3xl text-white font-semibold">Berlin, Germany</h1>
        <h3 class="text-white text-lg">Tuesday, Aug 5, 2025</h3>
      </div>
  
      <div class="flex items-center gap-4">
        <img src="/images/icon-sunny.webp" alt="icon-sunny" class="w-30" />
        <h1 class="text-white text-[5rem] font-semibold italic">
          20°
        </h1>
      </div>
    </section>
  
    <section class="grid grid-cols-[repeat(auto-fit,minmax(120px,1fr))] gap-3 ">
      <div class="text-white bg-neutral-700 p-3 space-y-4 rounded-lg border-2 border-neutral-800">
        <p class="text-lg">Feels Like</p>
        <span class="text-3xl">18°</span>
      </div>
  
      <div class="text-white bg-neutral-700 p-3 space-y-4 rounded-lg border-2 border-neutral-800">
        <p class="text-lg">Humidity</p>
        <span class="text-3xl">46%</span>
      </div>
  
      <div class="text-white bg-neutral-700 p-3 space-y-4 rounded-lg border-2 border-neutral-800">
        <p class="text-lg">Wind</p>
        <span class="text-3xl">14 km/h</span>
      </div>
      <div class="text-white bg-neutral-700 p-3 space-y-4 rounded-lg border-2 border-neutral-800">
        <p class="text-lg">Precipitation</p>
        <span class="text-3xl">0 mm</span>
      </div>
    </section>
  </div>
</template>
