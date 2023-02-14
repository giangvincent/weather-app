<template>
  <div class="flex flex-col min-h-screen font-Roboto bg-weather-primary">
    <SiteNav />
    <RouterView />
  </div>
</template>

<script>
import { RouterView } from "vue-router";
import SiteNav from "./components/SiteNav.vue";
export default {
  setup() {
    return {};
  },
  components: { SiteNav },
};
</script>

<style lang="scss" scoped>
</style>