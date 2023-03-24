<script>
import AppTitle from "./AppTitle.vue";

export default {
  components: {
    AppTitle,
  },
};
</script>

<template>
  <div id="jumbotron">
    <div class="container">
      <div class="text-box">
        <AppTitle />
      </div>
    </div>
  </div>
</template>

<style scoped>
#jumbotron {
  height: 100vh;
  display: flex;
  align-items: center;
  background-image: url(/mountainok.webp);
  background-size: cover;
  filter: contrast(0.8);
  background-position: bottom;
}

#jumbotron .text-box {
  padding: 20px;
  border-radius: 10px;
  background-color: rgba(255, 255, 255, 0.6);
}
</style>
