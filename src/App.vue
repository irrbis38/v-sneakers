<script setup>
import CardItem from './components/CardItem.vue';
</script>

<template>
  <CardItem title="Кроссовки Puma" :price="9500" is-added>
    <button class="text-gray-500">Добавить</button>
  </CardItem>
  <CardItem title="Кроссовки Nike" :price="11500" :is-added="false"/>
  <CardItem title="Кроссовки Kike" :price="1500" :is-added="false"/>
</template>

<style scoped>
</style>
