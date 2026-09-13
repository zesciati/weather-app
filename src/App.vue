<script setup lang="ts">
import WeatherCard from './components/WeatherCard.vue';
import WeatherSearchScreen from './components/WeatherSearchScreen.vue';
import TemplateWeatherApp from './template/TemplateWeatherApp.vue';


</script>

<template>
  <TemplateWeatherApp>
    <WeatherSearchScreen/>
    <WeatherCard/>
  </TemplateWeatherApp>
</template>

<style scoped></style>
