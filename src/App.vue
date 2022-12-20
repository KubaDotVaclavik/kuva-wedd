<script setup lang="ts">
import backgroundImg from "./assets/bkg-small.png";
</script>

<template>
  <div
    class="relative shadow-md h-[690px] w-[430px] bg-bottom bg-fit bg-no-repeat"
    :style="{ backgroundImage: `url(${backgroundImg})` }"
  >
    <div class="bg-gradient absolute w-full h-full">
      <h1 class="text-4xl text-center font-mirage mt-20">Šárka + Jakub</h1>
      <h2 class="text-4xl text-center font-astralaga mt-20">Šárka + Jakub</h2>
    </div>
  </div>
</template>
