<script setup>
import MyButton from "./MyButton.vue";
</script>

<template>
  <section
    class="flex flex-col xl:flex-row gap-10 xl:gap-4 justify-between font-bold text-white w-full mt-60 lg:px-40"
  >
    <div class="flex flex-col self-start mt-14 basis-0 px-5">
      <h1 class="text-6xl lg:text-7xl tracking-tighter leading-[79.2px]">About Us</h1>
      <div class="mt-12 text-lg tracking-tight leading-7 max-lg:mt-10">
        We’re a team of four passioned people. <br />
        <br />
        <span class="font-light"
          >We’re ready to take the world by storm and</span
        >
        <br />
        <span class="font-light">let you find new travel opportunities.</span>
        <br />
        <br />
        <span class="font-light"
          >Our everyday task is to make sure that you satisfied with the
          services and products that we provide.</span
        >
        <br />
        <br />
        With 💖 from Amsterdam, Netherlands.
      </div>
      <MyButton text="READ MORE ABOUT US" class="mt-10" />
    </div>

    <div class="flex relative px-24 lg:px-0 z-10 min-w-0">
      <div class="flex flex-wrap z-10 relative">
        <div
          class="members w-full lg:w-1/2 lg:h-1/2 bg-cover min-h-0 relative"
          id="member-1"
        >
          <img
            src="../assets/img/pic-1.png"
            alt=""
            class="flex-1 w-full h-full object-cover relative"
          />
          <div
            class="uppercase bg-white text-[#011627] text-sm md:text-lg px-5 py-5 rounded-lg absolute top-[60%] left-[-50px] z-40"
          >
            Martin Jack, <span class="text-teal-300">CEO</span>
          </div>
        </div>
        <div
          class="members w-full lg:w-1/2 lg:h-1/2 bg-cover min-h-0"
          id="member-2"
        >
          <img
            src="../assets/img/pic-2.png"
            alt=""
            class="flex-1 w-full h-full object-cover relative"
          />
        </div>
        <div
          class="members w-full lg:w-1/2 lg:h-1/2 bg-cover min-h-0"
          id="member-3"
        >
          <img
            src="../assets/img/pic-3.png"
            alt=""
            class="flex-1 w-full h-full object-cover relative"
          />
        </div>
        <div
          class="members w-full lg:w-1/2 lg:h-1/2 bg-cover min-h-0"
          id="member-4"
        >
          <img
            src="../assets/img/pic-4.png"
            alt=""
            class="flex-1 w-full h-full object-cover relative"
          />
        </div>
      </div>
      <img
        src="../assets/icons/dots-rectangular.svg"
        alt="dots"
        class="absolute top-[50%] translate-y-[-50%] right-[-10px] translate-x-[100%] z-0"
      />
    </div>
  </section>
</template>
