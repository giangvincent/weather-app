<template>
  <header class="sticky top-0 shadow-lg bg-weather-primary">
    <nav
      class="container flex flex-col items-center gap-4 py-6 text-white  sm:flex-row"
    >
      <RouterLink :to="{ home }">
        <div class="flex items-center flex-1 gap-3">
          <i class="text-2xl fa-solid fa-sun"></i>
          <p class="text-2xl">Local Weather</p>
        </div>
      </RouterLink>

      <div class="flex justify-end flex-1 gap-3">
        <i
          class="text-xl duration-150 cursor-pointer  fa-solid fa-circle-info hover:text-weather-secondary"
        ></i>
        <i
          class="text-xl duration-150 cursor-pointer  fa-solid fa-plus hover:text-weather-secondary"
        ></i>
      </div>

      <base-modal>
        <h1>Hello</h1>
      </base-modal>
    </nav>
  </header>
</template>

<script>
import { RouterLink } from "vue-router";
import BaseModal from "./BaseModal.vue";
export default {
  components: { BaseModal },
  setup() {
    return {};
  },
};
</script>