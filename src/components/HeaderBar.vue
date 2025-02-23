<script setup>
import logo from "../assets/dreiestos.png";
</script>

<template>
  <header class="p-4" id="bg-hijau">
    <div class="grid justify-items-center">
      <img :src="logo" alt="logo" class="max-w-[200px] md:max-w-[250px] lg:max-w-[400px] xl:max-w-[450px]" /> 
    </div>
  </header>
</template>

<style scoped>
#bg-hijau {
  background-color: #578e7e;
}
</style>
