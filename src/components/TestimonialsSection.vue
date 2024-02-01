<script setup>
import Card from "./Card.vue";
</script>

<template>
  <section
    class="flex justify-center items-center self-stretch md:px-16 py-12 w-full bg-slate-900 mt-60 mb-40 relative"
  >
    <div class="absolute top-[-40px] left-[50%] translate-x-[-50%] h-[70px] w-[2px] bg-white"></div>
    <div class="flex flex-col mt-14 mb-12 max-w-full w-[1044px] max-md:my-10">
      <h1
        class="self-center text-5xl lg:text-7xl font-bold tracking-[3.6px] text-center text-white leading-[79.2px]"
      >
        People’s thoughts
      </h1>
      <div
        class="self-center mt-11 text-xl lg:text-2xl font-bold leading-9 text-center text-white tracking-[3.6px] max-md:mt-10 max-md:max-w-full"
      >
        SEE WHAT ARE OTHERS SAYING
      </div>

      <div class="mt-20 max-md:mt-10 max-md:max-w-full">
        <div class="flex max-md:flex-col max-md:gap-0 flex-wrap">
          <div class="flex flex-col w-full xl:w-6/12 px-2 mb-4" v-for="i in 4" :key="i">
            <Card />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
