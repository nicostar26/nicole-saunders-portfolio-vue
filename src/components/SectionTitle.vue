<script setup>
const props = defineProps({
  title: String,
});
</script>

<template>
  <div class="w-100 flex justify-center pt-12">
    <div class="text-6xl text-gray-300">{{ title }}</div>
  </div>
</template>

<style></style>
