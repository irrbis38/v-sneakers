<template>
  <div class="flex flex-col gap-4 mb-6">
    <div class="flex items-end gap-2">
      <span>Итого:</span>
      <div class="relative -top-1 flex-1 border-b border-dashed"></div>
      <b>12999 руб.</b>
    </div>

    <div class="flex items-end gap-2">
      <span>Налог 5%:</span>
      <div class="relative -top-1 flex-1 border-b border-dashed"></div>
      <b>649 руб.</b>
    </div>

    <button
      type="button"
      class="w-full mt-5 py-3 rounded-xl transition text-white bg-lime-500 hover:bg-lime-600 active:bg-lime-700 disabled:bg-slate-400"
    >
      Оформить
    </button>
  </div>
</template>