<script setup>
import LogoTailwind from "../assets/tailwind.svg";
import LogoVue from "../assets/vuejs.svg";
</script>

<template>
  <div
    class="grid grid-cols-1 justify-items-stretch pt-2 pb-6 xl:pt-5 xl:pb-10 rounded-xl"
    id="bg-cream-tua"
  >
    <h1 class="font-bold text-base lg:text-xl justify-self-center" id="playfair-display">
      Created with Passion
    </h1>
    <h2 class="justify-self-center text-sm lg:text-base" id="dm-sans">
      Using Vue JS and Tailwind CSS
    </h2>
    <div class="flex justify-center gap-x-1 mt-3 lg:mt-5">
      <img :src="LogoVue" alt="" class="max-w-[22px] lg:max-w-[26px]" />
      <img :src="LogoTailwind" alt="" class="max-w-[26px] lg:max-w-[30px]" />
    </div>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,100..1000;1,9..40,100..1000&display=swap");

#playfair-display {
  font-family: "Playfair Display", serif;
  font-optical-sizing: auto;
  font-weight: weight;
  font-style: normal;
}

#dm-sans {
  font-family: "DM Sans", serif;
  font-optical-sizing: auto;
  font-weight: weight;
  font-style: normal;
}

#bg-cream-tua {
  background-color: #f5ecd5;
}
</style>
