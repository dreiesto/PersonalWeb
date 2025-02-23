<script setup>
import ig from "../../assets/instagram-icon.png";
import ln from "../../assets/linkedin-icon.png";
</script>

<template>
  <div>
    <h1 class="cream-tua font-medium text-xs lg:text-base block md:hidden mb-1">
      Social Media
    </h1>
    <h1 class="cream-tua font-medium text-xs lg:text-base hidden md:block mb-1">
      Find me in Social Media
    </h1>
    <div>
      <a href="https://www.instagram.com/dreiestos/">
        <button class="cursor-pointer mr-1">
          <img :src="ig" alt="" class="max-w-[15px] lg:max-w-[25px]" />
        </button>
      </a>
      <a href="https://www.linkedin.com/in/aariestos/"
        ><button class="cursor-pointer">
          <img :src="ln" alt="" class="max-w-[15px] lg:max-w-[25px]" /></button
      ></a>
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

#bg-hijau {
  background-color: #578e7e;
}
.cream-tua {
  color: #f5ecd5;
}
</style>
