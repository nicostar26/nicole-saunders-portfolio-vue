<script setup>
import SectionTitle from "./SectionTitle.vue";
import ExpertiseBox from "./ExpertiseBox.vue";
</script>

<template>
  <SectionTitle title="My Expertise" />

  <div class="bg-black grid grid-cols-3 gap-16 w-100 px-12 justify-center">
    <ExpertiseBox
      box-title="Software Development"
      box-description="Experienced in Attractive, Mobile Friendly Web and Software Development"
    />
    <ExpertiseBox
      box-title="Front-End Development"
      box-description="Passionate about UI/UX Design using VUE and REACT"
    />
    <ExpertiseBox
      box-title="Content Management"
      box-description="Over 5 Years of Experience using WordPress and Duda"
    />
  </div>
</template>

<style></style>
