<script setup>
import Header from "./components/HeaderBar.vue";
import HeroSection from "./components/HeroSection.vue";
import Portfo from "./components/Portfo.vue";
import Skill from "./components/Skill.vue";
import Created from "./components/Created.vue";
import Footer from "./components/Footer.vue";
import DiscoverMe from "./components/DiscoverMe.vue";
</script>

<template>
  <div class="flex flex-col min-h-screen" id="bg-cream-muda">
    <Header class="drop-shadow-lg" />
    <HeroSection class="mx-5 md:mx-10 lg:mx-20 xl:mx-40 mt-10"/>
    <Skill class="flex mx-5 md:mx-10 lg:mx-20 xl:mx-40 mt-10" />
    <portfo class="flex justify-center mx-5 md:mx-10 lg:mx-20 xl:mx-40 mt-10"/>
    <DiscoverMe class="flex justify-center mx-5 md:mx-10 lg:mx-20 xl:mx-40 mt-10" />
    <Created class="flex justify-center mx-5 md:mx-10 lg:mx-20 xl:mx-40 mt-10" />
    <Footer class="mt-10" />
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Afacad+Flux:wght@100..1000&display=swap");
#afacad-flux {
  font-family: "Afacad Flux", cursive;
}

#bg-cream-muda {
  background-color: #fffaec;
}

#hijau {
  background-color: #578e7e;
}
</style>
