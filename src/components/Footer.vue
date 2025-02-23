<script setup>
import socialmedia from "./footer/SocialMedia.vue";
import sourcecode from "./footer/SourceCode.vue";
</script>

<template>
  <footer class="text-white p-4" id="bg-hijau">
    <div class="md:mb-3 grid grid-cols-3">
      <socialmedia class=" justify-items-start" />
      <div class="justify-items-center">
        <img src="../assets/dreiestos.png" alt=""/>
      </div>
      <sourcecode class="justify-items-end" />
    </div>
    <h1 class="cream-tua text-xs lg:text-sm font-semibold uppercase tracking-widest justify-self-center" id="dm-sans">
      © 2025 Andre Ariesto Siregar
    </h1>
  </footer>
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

#bg-hijau {
  background-color: #578e7e;
}
.cream-tua {
  color: #f5ecd5;
}
</style>
