<template>
  <div class="lg:max-w-fit lg:mx-auto">
    <main class="p-4 space-y-6 font-dmsans templateweather">
      <slot />
    </main>
  </div>
</template>

<style>
@media screen and (min-width: 1024px) {
  .templateweather {
    display: grid;
    grid-template-columns: 2fr 1fr;
    grid-template-rows: auto auto auto;
    gap: 1.5rem;
    grid-template-areas:
      "search search"
      "card hourly"
      "daily hourly";
  }
}
</style>
