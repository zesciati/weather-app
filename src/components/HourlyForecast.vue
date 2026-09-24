<script setup lang="ts">
import DayHourlyForecast from "./littlecomponents/DayHourlyForecast.vue";
</script>

<template>
  <section class="bg-neutral-800 py-4 px-3 rounded-lg space-y-4">
    <div class="flex justify-between text-white font-semibold items-center">
      <h3>Hourly forecast</h3>
      <div class="dropdown dropdown-end">
        <div
          class="flex items-center bg-neutral-600 rounded-lg py-1.5 px-3 gap-2.5"
          tabindex="0"
          role="button"
        >
          <p class="text-neutral-0 text-sm">Tuesday</p>
          <img src="/images/icon-dropdown.svg" alt="icon-dropdown" />
        </div>
        <DayHourlyForecast />
      </div>
    </div>

    <article class="space-y-3">
      <div
        class="flex items-center justify-between text-white px-3 pr-4 bg-neutral-700 rounded-lg"
      >
        <div class="flex items-center gap-1">
          <img
            src="/images/icon-overcast.webp"
            alt="icon"
            class="max-inline-10 h-auto"
          />
          <p class="font-medium text-lg">3 PM</p>
        </div>
        <p class="text-sm">20°</p>
      </div>

      <div
        class="flex items-center justify-between text-white px-3 pr-4 bg-neutral-700 rounded-lg"
      >
        <div class="flex items-center gap-1">
          <img
            src="/images/icon-overcast.webp"
            alt="icon"
            class="max-inline-10 h-auto"
          />
          <p class="font-medium text-lg">3 PM</p>
        </div>
        <p class="text-sm">20°</p>
      </div>

      <div
        class="flex items-center justify-between text-white px-3 pr-4 bg-neutral-700 rounded-lg"
      >
        <div class="flex items-center gap-1">
          <img
            src="/images/icon-overcast.webp"
            alt="icon"
            class="max-inline-10 h-auto"
          />
          <p class="font-medium text-lg">3 PM</p>
        </div>
        <p class="text-sm">20°</p>
      </div>
    </article>
  </section>
</template>
