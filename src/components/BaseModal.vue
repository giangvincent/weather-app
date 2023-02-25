<template>
  <div
    class="absolute top-0 left-0 flex justify-center w-full h-screen px-0 bg-black  bg-opacity-30"
  >
    <div class="self-start max-w-screen-md p-4 mt-32 bg-white">
      <slot />
      <button class="px-6 py-2 mt-8 text-white bg-weather-primary">
        Close
      </button>
    </div>
  </div>
</template>

<script>
export default {
  setup() {
    return {};
  },
};
</script>