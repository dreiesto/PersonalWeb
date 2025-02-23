<script setup>
import PortfoCard from "./card/PortfoCard.vue";
import card1 from "../assets/programmer.png";
import card2 from "../assets/creative.png";
import card3 from "../assets/uiux.png";
</script>

<template>
  <div
    class="bg-hijau rounded-xl grid auto-cols-max justify-items-stretch pt-5 pb-25"
  >
    <h1
      class="cream-tua font-bold lg:text-xl justify-self-center"
      id="playfair-display"
    >
      My Portfolio
    </h1>
    <h2 class="cream-tua justify-self-center text-sm lg:text-base" id="dm-sans">
      Here are some of my works
    </h2>
    <div class="grid grid-cols-3 gap-1 md:gap-3 mt-10 justify-self-center" id="dm-sans">
      <PortfoCard
        :image="card1"
        title="Programming"
        description="Here you will see my work <br> <strong>Web Programming</strong> and <strong>Robotics</strong>."
      />
      <PortfoCard
        :image="card2"
        title="Creative"
        description="Here you will see my work <br> <strong>Graphics Design</strong> and <strong>Video Editing</strong>."
      />
      <PortfoCard
        :image="card3"
        title="UI/UX"
        description="Here you will see my work <br> <strong>UI/UX Design</strong>."
      />
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

.cream-tua {
  color: #f5ecd5;
}

.bg-hijau {
  background-color: #578e7e;
}
</style>
