<!-- src/App.vue -->
<template>
  <h1>{{ message }}</h1>
</template>

<script setup lang="ts">
import { ref } from "vue";

const message = ref("Hello World from Vue 3 + TypeScript!");
</script>
