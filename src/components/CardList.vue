<script setup>
import Card from './Card.vue'

defineProps({
  items: Array
})

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
      v-for="item in items"
      :key="item.id"
      :title="item.title"
      :img-url="item.imageUrl"
      :price="item.price"
      :is-added="true"
      :is-favorite="true"
      :on-click-add="onClickAdd"
      :on-click-favorite="onClickFavorite"
    />
  </div>
</template>