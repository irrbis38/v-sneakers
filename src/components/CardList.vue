<script setup>
import Card from './Card.vue'

const onClickAdd = () => {
  console.log('add')
}
const onClickFavorite = () => {
  console.log('favorite')
}
</script>


<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      title="Мужские кроссовки Nike Blazer Mid Suede"
      img-url="/sneakers/sneakers-1.jpg"
      :price="7000"
      :is-added="true"
      :is-favorite="true"
      :on-click-add="onClickAdd"
      :on-click-favorite="onClickFavorite"
    />
  </div>
</template>