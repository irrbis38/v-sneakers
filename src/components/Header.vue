<template>
  <header class="flex justify-between border-b border-slate-300 px-10 py-8">
    <div class="flex items-center gap-4">
      <img class="block w-10 h-10" src="/logo.png" alt="logo" />
      <div>
        <h1 class="text-xl uppercase font-bold">Vue Sneakers</h1>
        <p class="text-slate-500">Магазин лучших кросовок</p>
      </div>
    </div>

    <ul class="flex items-center gap-10">
      <li
        class="flex items-center gap-3 text-gray-500 hover:text-black cursor-pointer transition-colors"
      >
        <img src="/cart.svg" alt="" />
        <b>1205 руб.</b>
      </li>
      <li
        class="flex items-center gap-3 text-gray-500 hover:text-black cursor-pointer transition-colors"
      >
        <img src="/heart.svg" alt="" />
        <b>Избранное</b>
      </li>
      <li
        class="flex items-center gap-3 text-gray-500 hover:text-black cursor-pointer transition-colors"
      >
        <img src="/profile.svg" alt="" />
        <b>профиль</b>
      </li>
    </ul>
  </header>
</template>