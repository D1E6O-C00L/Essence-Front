<template>
  <header class="flex items-center justify-between px-6 h-20 bg-white shadow-md">
    <h1 class="text-3xl font-bold text-[#e9552f]">Essence</h1>

    <ul class="flex gap-6 text-base text-[#2f1e13] font-medium list-none">
      <li>Calzado</li>
      <li>Hombre</li>
      <li>Mujer</li>
      <li>Deporte</li>
    </ul>

    <div class="flex items-center gap-4">
      <!-- Input con lupa -->
      <div class="flex items-center bg-[#fbf8f4] rounded-full px-4 h-[45px] w-[261px]">
        <MagnifyingGlassIcon class="w-5 h-5 text-[#343a40] mr-2" />
        <input
          type="text"
          placeholder="Buscar"
          class="bg-transparent outline-none text-[#343a40] w-full placeholder:text-[#aaa]"
        />
      </div>

      <!-- Íconos -->
      <ShoppingBagIcon class="w-6 h-6 text-[#343a40]" />
      <UserIcon class="w-6 h-6 text-[#343a40]" />
    </div>
  </header>
</template>

<script setup lang="ts">
import { UserIcon, ShoppingBagIcon, MagnifyingGlassIcon } from '@heroicons/vue/24/outline'
</script>
