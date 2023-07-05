<template>
  <TheHeader />
  <main>
    <TheSlider />
    <TheCategories />
    <TheServices />
    <TheTours />
  </main>
</template>

<script setup>
import TheHeader from "./components/TheHeader.vue";
import TheSlider from "./components/TheSlider.vue";
import TheCategories from "./components/TheCategories.vue";
import TheServices from "./components/TheServices.vue";
import TheTours from "./components/TheTours.vue";
</script>

<style lang="scss">
main {
  section {
    padding: 3rem 1rem 0;

    h3 {
      font-size: 2rem;
      text-transform: capitalize;
    }
  }
}
</style>