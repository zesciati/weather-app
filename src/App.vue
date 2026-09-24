<script setup lang="ts">
import DailyForecast from "./components/DailyForecast.vue";
import HourlyForecast from "./components/HourlyForecast.vue";
import DayHourlyForecast from "./components/littlecomponents/DayHourlyForecast.vue";
import SwitchToImperials from "./components/littlecomponents/SwitchToImperials.vue";
import WeatherCard from "./components/WeatherCard.vue";
import WeatherSearchScreen from "./components/WeatherSearchScreen.vue";
import TemplateWeatherApp from "./template/TemplateWeatherApp.vue";
</script>

<template>
  <!-- <TemplateWeatherApp>
    <WeatherSearchScreen class="area-search" />
    <WeatherCard class="area-card" />
    <DailyForecast class="area-daily" />
    <HourlyForecast class="area-hourly" />
  </TemplateWeatherApp> -->

  <SwitchToImperials/>
  <!-- <DayHourlyForecast /> -->
</template>

<style>
@media screen and (min-width: 1024px) {
  .area-search {
    grid-area: search;
  }

  .area-card {
    grid-area: card;
  }

  .area-daily {
    grid-area: daily;
  }

  .area-hourly {
    grid-area: hourly;
  }
}
</style>
