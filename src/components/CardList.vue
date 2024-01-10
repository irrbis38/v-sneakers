<script setup>
import Card from './Card.vue'
</script>


<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      title="Мужские кроссовки Nike Blazer Mid Suede"
      img-url="/sneakers/sneakers-1.jpg"
      :price="7000"
    />
    <Card
      title="Мужские кроссовки Nike Blazer Mid"
      img-url="/sneakers/sneakers-2.jpg"
      :price="9000"
    />
    <Card
      title="Мужские кроссовки Nike Blazer Mid Suede"
      img-url="/sneakers/sneakers-3.jpg"
      :price="7000"
    />
    <Card
      title="Мужские кроссовки Nike Blazer Mid Suede"
      img-url="/sneakers/sneakers-4.jpg"
      :price="5000"
    />
  </div>
</template>