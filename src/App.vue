<script setup lang="ts">
import DailyForecast from "./components/DailyForecast.vue";
import HourlyForecast from "./components/HourlyForecast.vue";
import WeatherCard from "./components/WeatherCard.vue";
import WeatherSearchScreen from "./components/WeatherSearchScreen.vue";
import TemplateWeatherApp from "./template/TemplateWeatherApp.vue";
</script>

<template>
  <TemplateWeatherApp>
    <WeatherSearchScreen />
    <WeatherCard />
    <DailyForecast />
    <HourlyForecast />
  </TemplateWeatherApp>
</template>

<style scoped></style>
