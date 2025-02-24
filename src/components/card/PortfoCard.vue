<script>
export default {
  props: {
    image: String,
    title: String,
    description: String,
  },
};
</script>

<template>
  <div
    class="grid grid-cols-1 rounded-xl xs:px-10 pt-5 pb-0 md:py-5 px-10 md:px-1 lg:px-2"
    id="bg-cream-tua"
  >
    <div class="justify-items-center">
      <img
        :src="image"
        :alt="title"
        class="max-w-[100px] md:max-w-[150px] lg:max-w-[200px] xl:max-w-[300px]"
      />
      <h2 class="font-bold text-xs sm:text-sm md:text-base lg:text-lg mt-5">
        {{ title }}
      </h2>
      <p
        class="text-[10px] sm:text-xs md:text-sm lg:text-base text-center max-w-[150px] xs:max-w-[200px] sm:max-w-[110px] md:max-w-[200px] lg:max-w-3xs mt-2"
        v-html="description"
      ></p>
    </div>
    <div class="grid grid-cols-1 content-end justify-self-center">
      <a href=""
        ><button
          class="bg-cream-muda rounded-full cursor-pointer p-3 md:p-5 translate-y-[20px] md:translate-y-[50px]"
        >
          <img
            src="../../assets/roket.png"
            alt=""
            class="max-w-[20px] md:max-w-[25px]"
          /></button
      ></a>
    </div>
  </div>
</template>

<style scoped>
#bg-cream-tua {
  background-color: #f5ecd5;
}

.bg-cream-muda {
  background-color: #fffaec;
}
</style>
