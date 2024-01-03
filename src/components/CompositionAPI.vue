<script setup>
import { ref } from 'vue';

const count = ref(0);

const increment = () => {
  count.value++
}

const update = (event) => {
  count.value = parseInt(event.target.value);
}
</script>

<template>
  <h2>{{ count }}</h2>
  <button @click="increment">Click me</button>
  <input @keyup.enter.ctrl="update" type="text">
</template>