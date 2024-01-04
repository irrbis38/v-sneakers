<script setup>
defineProps({
  title: String,
  price: Number,
  isAdded: Boolean
})
</script>

<template>
  <div class="product mb-40 font-bold">
    <h3>Товар: {{ title }}</h3>
    <p>Цена: {{ price }}</p>
    <p>Добавлен: {{ isAdded }}</p>
    <slot></slot>
  </div>
</template>

<!-- <style scoped>
.product {
  border: 1px solid rgb(165, 174, 248);
  padding: 10px;
  margin-bottom: 10px;
}
</style> -->