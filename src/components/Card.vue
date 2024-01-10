<script setup>
defineProps({
  title: String,
  imgUrl: String,
  price: Number
})
</script>

<template>
  <div
    class="relative border border-slate-100 bg-white rounded-3xl p-8 cursor-pointer transition hover:-translate-y-2 hover:shadow-xl"
  >
    <img src="/like-1.svg" alt="like" class="absolute top-8 left-8" />
    <img :src="imgUrl" alt="" />
    <p class="mt-2">{{ title }}</p>

    <div class="flex justify-between mt-2">
      <div class="flex flex-col">
        <span class="text-slate-00">Цена:</span>
        <b>{{ price }} руб.</b>
      </div>
      <img src="/plus.svg" alt="Plus" />
    </div>
  </div>
</template>