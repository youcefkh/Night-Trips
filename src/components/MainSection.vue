<script setup>
import AboutSection from "./AboutSection.vue";
import TestimonialsSection from "./TestimonialsSection.vue";
import TripSection from "./TripSection.vue";
import Vectors from "./Vectors.vue";
</script>

<template>
  <main class="w-screen overflow-hidden relative">
    <Vectors class="z-0 absolute top-0 left-0 w-full h-full" />
    <img src="../assets//img/mountain.png" alt="" class="z-0 absolute bottom-[1500px] left-0">
    <div class="absolute bottom-[700px] left-0 w-full h-[800px] bg-[#011627] z-0"></div>
    <div class="relative z-10 px-0 md:px-20 lg:px-40 mx-4">
      <TripSection />
      <AboutSection />
      <TestimonialsSection />
      <div class="flex flex-col mt-14 max-w-full w-full max-md:my-10 mb-40 pb-40 relative">
        <h1
          class="self-center text-6xl lg:text-7xl font-bold tracking-[3.6px] text-center text-white leading-[79.2px]"
        >
          See you soon!
        </h1>
        <div
          class="self-center mt-11 text-2xl font-bold leading-9 text-center text-white tracking-[3.6px] max-md:mt-10 max-md:max-w-full"
        >
          we hope to meet each other <br />very soon.
        </div>

        <div class="absolute bottom-0 left-[50%] translate-x-[-50%] h-[70px] w-[2px] bg-white"></div>
      </div>
    </div>
  </main>
</template>

<style scoped>
main {
  background-color: #011627;
}
</style>
