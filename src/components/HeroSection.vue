<script setup>
import MyButton from './MyButton.vue';
</script>

<template>
  <header
    id="hero"
    class="flex overflow-hidden relative flex-col pt-8 px-20 lg:px-60 w-full min-h-screen"
  >
    <nav
      class="flex relative gap-6 justify-between items-center self-end text-base font-bold tracking-widest text-white uppercase whitespace-nowrap"
    >
      <i class="fa-solid fa-magnifying-glass text-2xl cursor-pointer"></i>
      <MyButton text="main" />
    </nav>

    <div
      class="flex relative flex-col max-w-full font-bold text-white w-[802px]"
    >
      <h1 class="text-4xl leading-[68.4px] max-md:max-w-full">
        NT <span class="text-teal-300">.</span>
      </h1>
      <h1
        id="heading"
        class="self-end mt-14 lg:mr-16 text-8xl lg:text-[120px] font-bold tracking-tight max-md:mt-10 max-md:max-w-full"
      >
        Night Trips
      </h1>
      <h2
        id="sub-heading"
        class="self-center font-bold mt-7 lg:ml-16 text-lg tracking-widest uppercase"
      >
        WE GOT TRIPS FOR THE TRIPPSTER IN YOU
      </h2>
      <p
        id="copy"
        class="self-end lg:pl-40 mt-8 font-normal leading-7 text-justify lg:text-center w-full lg:w-[777px] max-md:mt-10 max-md:max-w-full"
      >
        Neque, eros commodo, nascetur ullamcorper vitae. Tincidunt ut venenatis,
        volutpat lorem ut faucibus mauris, quisque. Integer gravida sed quis
        congue. Vel risus, arcu a viverra leo id pulvinar ultricies. Enim in in
        in pulvinar nulla sollicitudin. Ullamcorper.
      </p>
    </div>
    <div
      class="flex relative flex-col items-center pt-8 pb-12 mt-60 max-md:px-5 max-md:mt-10 max-md:max-w-full z-10"
    >
      <div
        class="flex relative gap-5 justify-between items-start px-px mb-24 w-full max-w-[1369px] max-md:flex-wrap max-md:mb-10 max-md:max-w-full"
      >
        <div class="flex flex-col gap-5">
            <p class="uppercase font-bold tracking-widest text-white rotate-[-90deg] absolute top-2 left-[-34px]">SCROLL</p>
            <div class="self-end bg-white w-0.5 h-20 rounded-xl max-md:mt-10 absolute bottom-[-32px] left-0"></div>
        </div>
        <div class="flex flex-col gap-5">
          <img src="../assets/icons/twitter.svg" alt="" class="cursor-pointer"/>
          <img src="../assets/icons/instagram.svg" alt="" class="cursor-pointer"/>
          <img src="../assets/icons/fb.svg" alt="" class="cursor-pointer"/>
        </div>
      </div>
    </div>

    <div
      id="bottom-shadow"
      class="absolute bottom-0 left-0 w-full h-[370px] z-0"
    ></div>
  </header>
</template>

<style lang="css" scoped>
#hero {
  background-image: url("../assets/img/hero-bg.png");
}
#bottom-shadow {
  background: linear-gradient(
    180deg,
    rgba(1, 22, 39, 0) 0%,
    #011627 76.64%,
    #011627 100%
  );
}
</style>
