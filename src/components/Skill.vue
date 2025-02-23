<script setup>
import SkillCard from "./card/SkillCard.vue";
import card1 from "../assets/logo-web.png";
import card2 from "../assets/logo-robotic.png";
import card3 from "../assets/logo-creative.png";
import card4 from "../assets/logo-uiux.png";
</script>

<template>
  <div
    class="grid pt-5 pb-10 rounded-xl"
    id="bg-cream-tua"
  >
    <h1 class="flex justify-center text-base lg:text-xl font-bold" id="playfair-display">
      My Competencies
    </h1>
    <h2 class="flex justify-center text-sm lg:text-base" id="dm-sans">
      I have several competencies that I can offer to you</h2>
    <div class="grid grid-cols-2 md:grid-cols-4 xl:grid-cols-4 gap-3 mt-10 cream-muda justify-self-center" id="dm-sans">
      <SkillCard
        :image="card1"
        title="Web Programming"
        description="Design and create a website from scratch or use a website builder."
      />
      <SkillCard
        :image="card2"
        title="Robotics"
        description="Design and build a robot from scratch and integrate it with your device if needed."
      />
      <SkillCard
        :image="card3"
        title="Creative"
        description="Create digital designs to fulfill different requirements based on your vision."
      />
      <SkillCard
        :image="card4"
        title="UI/UX"
        description="Create and design a good user interface based on user experience."
      />
    </div>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap");

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

.cream-muda {
  color: #fffaec;
}
</style>
