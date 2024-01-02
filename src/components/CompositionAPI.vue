<script setup>
import { ref } from 'vue';

const count = ref(0);

const increment = () => {
  count.value++
}
</script>

<template>
  <h2>{{ count }}</h2>
  <button @click="increment">Click me</button>
</template>