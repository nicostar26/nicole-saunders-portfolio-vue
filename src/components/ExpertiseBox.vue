<script setup>
const props = defineProps({
  boxTitle: String,
});
</script>

<template>
  <div class="text-gray-300 border-2 rounded p-2 my-6">
    <h2 class="text-xl uppercase">{{ boxTitle }}</h2>
  </div>
</template>

<style></style>
