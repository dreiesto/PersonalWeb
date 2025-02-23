<script setup>
import foto from "../assets/foto.jpg";
</script>

<template>
  <div class="grid grid-flow-col gap-x-5 rounded-xl">
    <div class="hidden md:block lg:block">
      <img
        :src="foto"
        alt="Photo Profile"
        class="md:max-w-[190px] lg:max-w-[230px] xl:max-w-[200px] rounded-2xl"
      />
    </div>

    <div class="content-center">
      <div class="block md:hidden lg:hidden justify-self-center mb-2.5">
        <img
          :src="foto"
          alt="Photo Profile"
          class="max-w-[100px] rounded-2xl"
        />
      </div>
      <div class="mb-4">
        <h1
          class="text-base md:text-lg lg:text-2xl xl:text-2xl text-center md:text-start lg:text-start font-extrabold uppercase"
          id="playfair-display"
        >
          Andre Ariesto Siregar
        </h1>
        <h2
          class="text-xs md:text-xs text-center md:text-start lg:text-start lg:text-sm font-semibold"
          id="dm-sans"
        >
          Tech Enthusiast / Design Enthusiast
        </h2>
      </div>
      <div class="mt-2">
        <p
          class="text-sm text-center md:text-start lg:text-start lg:text-base"
          id="dm-sans"
        >
          Hi, nice to meet you. I have a great interest in technology and am
          eager to continue learning and growing. I am open to new opportunities
          and want to develop myself in various fields, both technology and
          non-technology related, to stay relevant with the development of the
          industry.
        </p>
        <div
          class="mt-4 cream-muda flex md:justify-self-start lg:justify-self-start justify-self-center"
          id="dm-sans"
        >
          <a href="mailto:aariestos@gmail.com"
            ><button
              class="py-1 px-3 rounded-full cursor-pointer mr-2 flex items-center gap-2"
              id="hijau"
            >
              <img
                src="../assets/gmail.png"
                alt=""
                class="max-w-5 lg:max-w-[20px]"
              />
              <h1 class="text-sm lg:text-base">Email</h1>
            </button></a
          >
          <a href="https://wa.me/6285179914149"
            ><button
              class="py-1 px-3 rounded-full cursor-pointer flex items-center gap-2"
              id="hijau"
            >
              <img
                src="../assets/wa.png"
                alt=""
                class="max-w-4 lg:max-w-[18px]"
              />
              <h1 class="text-sm lg:text-base">WhatsApp</h1>
            </button></a
          >
        </div>
      </div>
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

#hijau {
  background-color: #578e7e;
}

.cream-muda {
  color: #fffaec;
}
</style>
