<script setup>
import DrawerHead from './DrawerHead.vue'
import DrawerList from './DrawerList.vue'
import DrawerFooter from './DrawerFooter.vue'
</script>

<template>
  <div class="hidden fixed top-0 left-0 w-full h-full z-2">
    <div class="absolute top-0 left-0 w-full z-1 h-full bg-black opacity-70"></div>
    <div class="absolute top-0 right-0 w-96 z-2 h-full p-8 bg-white flex flex-col gap-5">
      <DrawerHead />

      <DrawerList />

      <DrawerFooter />
    </div>
  </div>
</template>