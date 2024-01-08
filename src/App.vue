<script setup>
import Header from './components/Header.vue'
import Card from './components/Card.vue'
</script>

<template>
  <div class="w-4/5 m-auto rounded-xl bg-white shadow-xl mt-14 mb-14">
    <Header />

    <div class="flex flex-wrap p-10 gap-10">
      <Card />
      <Card />
      <Card />
      <Card />
    </div>
  </div>
</template>

<style scoped>
</style>
