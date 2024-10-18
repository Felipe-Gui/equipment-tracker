<script setup lang="ts">
import MapComponent from './components/MapComponent.vue'
import FooterComponent from './components/FooterComponent.vue';
import TopbarComponent from './components/TopbarComponent.vue';
</script>

<template>
  <TopbarComponent />
  <div class="custom-container">
    <MapComponent />
  </div>
  <FooterComponent />
</template>

<style scoped>
</style>
