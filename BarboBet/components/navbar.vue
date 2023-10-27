<template>
  <div
    class="w-full h-9 bg-gray-900 text-white flex justify-between px-8 py-8 text-xl"
  >
    <aside class="flex gap-5 items-center">
      <button
        class="h-8 aspect-square rounded-full"
        style="background: #6366f1"
      ></button>

      <button class="navbar-button">BET</button>

      <button class="navbar-button">TRENDING</button>
      <button class="navbar-button">STATISTICS</button>
    </aside>
    <aside>
      <div class=""></div>
    </aside>
  </div>
</template>

<style scoped>
.navbar-button {
  @apply   rounded-lg hover:bg-gray-900  focus:bg-gray-600 active:bg-gray-400  px-5 py-2 text-sm font-semibold text-white ;
}
</style>
