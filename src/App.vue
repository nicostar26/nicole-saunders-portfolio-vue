<script setup>
import Footer from "./components/Footer.vue";
import MyExpertise from "./components/MyExpertise.vue";
</script>

<template>
  <div class="wrapper">
    <video margin="0" autoplay loop>
      <source src="./assets/header-video.mp4" type="video/mp4" />
    </video>
    <MyExpertise />
    <Footer />
  </div>
</template>

<style scoped>
@import "./style.css";
.wrapper {
  padding: 0px;
  margin: 0px;
}
video {
  width: 100%;
  height: 100%;
  border-bottom: 0.1rem #ac8c3c solid;
}
</style>
