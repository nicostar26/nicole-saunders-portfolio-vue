<script setup>
const props = defineProps({
  boxTitle: String,
  boxDescription: String,
});
</script>

<template>
  <div class="text-gray-300 border-2 rounded p-2 my-6">
    <div class="flex">
      <h2 class="text-xl uppercase">{{ boxTitle }}</h2>
    </div>
    <div class="flex">
      <div class="w-24">
        <img src="../assets/code-bar-white.png" />
      </div>
      <div class="mt-4 text-sm">{{ boxDescription }}</div>
    </div>
  </div>
</template>

<style></style>
