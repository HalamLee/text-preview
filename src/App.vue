<template>
  <div class="container"><PhoneFrame /></div>
</template>

<script setup lang="ts">
import PhoneFrame from './components/PhoneFrame.vue';
</script>

<style>
body {
  margin: 0;
}
</style>

<style scoped>
.container {
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
