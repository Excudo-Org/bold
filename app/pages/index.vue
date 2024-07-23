<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
const msg = 'Hello Hooked & Bold!';
</script>

<template>
  <div>
    <h1 class="center-text">{{ msg }}</h1>
  </div>
</template>

<style scoped>
div {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100dvh;
  font-family: Arial, sans-serif;
  font-size: 4.5rem;
  color: #333;
}
h1 {
  font-weight: bold;
}
.center-text {
  text-align: center;
}
</style>
