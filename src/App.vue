<template>
  <div class="content">
    <h1>Rsbuild with Vue [PROVIDER]</h1>
    <p>Start building amazing things with Rsbuild.</p>

    <Button></Button>
  </div>
</template>

<script setup lang="ts">
import Button from "./button.vue";
</script>

<style scoped>
.content {
  display: flex;
  min-height: 100vh;
  line-height: 1.1;
  text-align: center;
  flex-direction: column;
  justify-content: center;
}

.content h1 {
  font-size: 3.6rem;
  font-weight: 700;
}

.content p {
  font-size: 1.2rem;
  font-weight: 400;
  opacity: 0.5;
}
</style>
