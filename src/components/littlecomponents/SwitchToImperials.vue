<script setup lang="ts"></script>

<template>
  <div class="text-neutral-0 flex justify-center items-center min-h-screen">
    <div class="bg-neutral-800 p-2 rounded-lg w-50">
      <button class="font-semibold">Switch to Imperial</button>
      <div class="divide-y divide-neutral-500">
        <div class="flex-col flex py-2 space-y-1">
          <span class="flex justify-between text-neutral-300 text-sm ">Temperature </span>
          <span class="flex justify-between hover:bg-neutral-700  p-1.5">Celcius (°C) <span>✓</span></span>
          <span class="flex justify-between p-1.5">Fahrenheit (°F) <span>✓</span></span>
        </div>
        <div class="flex-col flex py-2 space-y-2">
          <span class="flex justify-between text-neutral-300 text-sm">Wind Speed </span>
          <span class="flex justify-between">km/h <span>✓</span></span>
          <span class="flex justify-between">mph  <span>✓</span></span>
        </div>
        <!-- <div class="flex-col flex py-2 space-y-2">
          <span class="flex justify-between text-neutral-300 text-sm">Precipitation </span>
          <span class="flex justify-between">Milimeters (mm) <span>✓</span></span>
          <span class="flex justify-between">Inches (in) <span>✓</span></span>
        </div> -->
      </div>
    </div>
  </div>
</template>
