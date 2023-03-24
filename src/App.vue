<script>
import AppHeader from "./components/AppHeader.vue";
import AppHero from "./components/AppHero.vue";
import AppTitle from "./components/AppTitle.vue";
import "@fontsource/roboto";

export default {
  components: {
    AppHeader,
    AppHero,
    AppTitle,
  },
};
</script>

<template>
  <AppHeader />
  <AppHero />
  <div class="container">
    <AppTitle />
  </div>
</template>

<style scoped></style>
