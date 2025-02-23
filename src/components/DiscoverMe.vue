<template>
  <div class="grid grid-cols-1 items-center">
    <div>
      <h1
        class="flex justify-center text-base lg:text-xl font-bold"
        id="playfair-display"
      >
        Discover Me
      </h1>
      <h2 class="flex justify-center text-sm lg:text-base" id="dm-sans">
        Through the articles I write
      </h2>
    </div>
    <div class="flex justify-center mt-3 lg:mt-6 xl:mt-6">
      <a href="https://medium.com/@aariestos.tech"
        ><button class="">
          <img
            src="../assets/medium.svg"
            alt=""
            class="max-w-[150px] xl:max-w-[300px] cursor-pointer"
          /></button
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
