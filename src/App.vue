<script setup>
import Footer from './components/Footer.vue';
</script>

<template>
  <div class="wrapper">
      <video margin="0" autoplay loop>
        <source src="./assets/header-video.mp4" type="video/mp4">
      </video> 

      <Footer />
  </div>

  
</template>

<style scoped>
@import './style.css';
.wrapper {
  padding: 0px;
  margin: 0px;
}
video {
  width: 100%;
  height: 100%;
  border-bottom: .1rem #ac8c3c solid;
}
</style>
