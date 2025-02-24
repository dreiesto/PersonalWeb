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
  <div class="rounded-xl py-5 px-2 xs:px-5 md:px-2" id="hijau">
    <div class="justify-items-center">
      <img :src="image" :alt="title" class="max-w-[40px] sm:max-w-[50px] lg:max-w-[60px] xl:max-w-[50px]" />
      <h2 class="font-bold text-center text-xs sm:text-sm lg:text-lg mt-5">{{ title }}</h2>
      <p class="text-[10px] sm:text-xs lg:text-base text-center max-w-[100px] sm:max-w-[150px] md:max-w-[135px] lg:max-w-[180px] xl:max-w-3xs mt-2">{{ description }}</p>
    </div>
  </div>
</template>

<style scoped>
#hijau {
  background-color: #578e7e;
}
</style>
