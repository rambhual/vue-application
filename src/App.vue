<template>
  <Navigation>
    <router-view />
  </Navigation>
</template>

<script>
import Navigation from "./components/Navigation.vue";

export default {
  name: "App",
  components: {
    Navigation,
  },
};
</script>

<style>
</style>
