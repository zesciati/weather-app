<script setup lang="ts">

</script>

<template>
  <div tabindex="-1" class="dropdown-content text-neutral-0 z-10 mt-2 ">
    <div class="bg-neutral-800 p-2 rounded-lg w-50 font-dmsans outline outline-neutral-600">
      <button
        class="font-semibold px-1.5 py-0.5 cursor-pointer text-left w-full hover:bg-neutral-700 hover:rounded-md focus:outline focus:outline-neutral-0 focus:rounded-md"
      >
        Switch to Imperial
      </button>
      <div class="divide-y divide-neutral-500">
        <div class="flex-col flex py-2">
          <span
            class="flex justify-between text-neutral-300 text-xs p-1.5 sm:text-sm"
            >Temperature</span
          >
          <span
            class="flex justify-between hover:bg-neutral-700 p-1.5 rounded-md text-sm sm:text-base"
            >Celcius (°C) <span>✓</span></span
          >
          <span
            class="flex justify-between hover:bg-neutral-700 p-1.5 rounded-md text-sm sm:text-base"
            >Fahrenheit (°F) <span>✓</span></span
          >
        </div>
        <div class="flex-col flex py-2">
          <span
            class="flex justify-between text-neutral-300 text-xs p-1.5 sm:text-sm"
            >Wind Speed</span
          >
          <span
            class="flex justify-between hover:bg-neutral-700 p-1.5 rounded-md text-sm sm:text-base"
            >km/h <span>✓</span></span
          >
          <span
            class="flex justify-between hover:bg-neutral-700 p-1.5 rounded-md text-sm sm:text-base"
            >mph <span>✓</span></span
          >
        </div>
        <div class="flex-col flex py-2">
          <span
            class="flex justify-between text-neutral-300 text-xs p-1.5 sm:text-sm"
            >Precipitation</span
          >
          <span
            class="flex justify-between hover:bg-neutral-700 p-1.5 rounded-md text-sm sm:text-base"
            >Milimeters(mm) <span>✓</span></span
          >
          <span
            class="flex justify-between hover:bg-neutral-700 p-1.5 rounded-md text-sm sm:text-base"
            >Inches (in) <span>✓</span></span
          >
        </div>
      </div>
    </div>
  </div>
</template>
