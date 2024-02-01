<script setup>
import MyButton from "./MyButton.vue";
</script>

<template>
  <section class="flex flex-col relative mb-40 px-0 lg:px-20 xl:px-40px">
    <div class="flex flex-col w-full max-lg:px-5 max-lg:max-w-full">
      <div
        class="flex flex-col lg:flex-row gap-7 justify-start items-center w-full self-start lg:ml-4 text-white max-lg:flex-wrap"
      >
        <h1
          class="text-7xl font-bold tracking-tighter whitespace-nowrap leading-[79.2px] w-max"
        >
          Pick your trip
        </h1>
        <button class="text-teal-300">
          <i class="fa-solid fa-x"></i>
        </button>
        <p>
          Our team put together some trips to you to discover, <br />
          feel free to discover each of them.
        </p>
      </div>
      <div
        class="flex gap-0 justify-between mt-24 font-bold text-center leading-[110%] w-full"
      >
        <div
          class="flex z-10 flex-col text-base tracking-tight text-white max-lg:max-w-full relative w-full"
        >
          <div class="flex gap-5 justify-between w-full">
            <div
              class="flex flex-col flex-auto self-start text-lg tracking-tight text-teal-300 whitespace-nowrap basis-0"
            >
              <div class="self-center cursor-pointer text-sm lg:text-lg">Chill Adventure</div>
              <div class="shrink-0 mt-9 h-1 bg-teal-300 rounded-xl"></div>
            </div>
            <div class="flex-auto text-gray-500 cursor-pointer text-sm lg:text-lg">
              Spooky Times
            </div>
            <div class="flex-auto text-gray-500 cursor-pointer text-sm lg:text-lg">
              Desert Madness
            </div>
            <div class="flex-auto text-gray-500 cursor-pointer text-sm lg:text-lg">
              Out in the wild
            </div>
          </div>
          <div
            class="shrink-0 mt-10 h-0.5 bg-teal-300 rounded-xl absolute bottom-0 left-0 w-full"
          ></div>
        </div>
      </div>
    </div>
    <div
      class="flex flex-col lg:flex-row gap-32 items-center justify-between px-5 mt-36 mb-20 w-full font-bold text-white"
    >
      <div
        class="min-w-[200px] max-w-[486px] w-[486px] h-[607px] flex-1 relative px-24 lg:px-0"
      >
        <div class="h-full rounded-lg overflow-hidden z-10 relative">
          <img
            loading="lazy"
            src="../assets/img/grand-dunes.png"
            class="flex-1 w-full h-full object-cover relative"
          />

          <div class="flex absolute bottom-0 right-0 z-20">
            <button class="text-white bg-[#011627] px-5 py-4 rounded-tl-lg">
              <i class="fa-solid fa-arrow-left"></i>
            </button>
            <div class="flex-1 w-[1px] bg-gray-800"></div>
            <button class="text-white bg-[#011627] px-5 py-4 rounded-br-lg">
              <i class="fa-solid fa-arrow-right"></i>
            </button>
          </div>
        </div>
        <img
          src="../assets/icons/dots.svg"
          alt="dots"
          class="absolute bottom-[-55px] left-[30px] lg:left-[-60px] z-0 h-[150px] lg:h-auto"
        />

        <div
          class="absolute top-9 left-[75px] sm:left-[60px] lg:top-[50%] lg:translate-y-[-50%] lg:left-[-60px] z-10 font-bold text-sm sm:text-xl lg:text-2xl tracking-[3.6px] leading-[36px]"
        >
          <div class="w-full h-[2px] bg-teal-300 absolute top-0 left-0"></div>
          <div class="w-[2px] h-[15px] bg-teal-300 absolute top-0 left-0"></div>
          <p class="text-teal-300 mt-4">01.</p>
          <p class="uppercase mt-4">
            grand dunes <br />
            landscape
          </p>
        </div>
      </div>

      <div class="div flex flex-col flex-1 self-start relative pb-10">
        <h1 class="text-6xl tracking-tighter leading-[71.5px]">
          Chill Adventure
        </h1>
        <div class="mt-16 text-base">
          <p class="font-semibold mb-6 tracking-tight leading-7">
            Ornare vivamus molestie pellentesque nunc. Sed sapien erat ultrices
            curabitur. Erat id fringilla arcu condimentum fames.
          </p>
          <p class="font-normal mb-7 tracking-tight leading-7">
            Aliquet dictum aliquet faucibus cursus turpis. Suspendisse cum
            rutrum sit ut sociis. Pellentesque neque orci adipiscing pharetra
            lacus, dignissim pharetra ipsum blandit. Feugiat quis quam
            consectetur lectus id quis tortor vel, mattis.
          </p>
        </div>
        <MyButton text="See our last offer" />
      </div>
      <div class="absolute bottom-0 right-4">
        <p
          class="uppercase text-white font-bold tracking-[3.6px] leading-[36px]"
        >
          share it:
        </p>
        <div class="flex gap-5 my-5 pr-5">
          <img src="../assets/icons/twitter.svg" alt="" class="cursor-pointer"/>
          <img src="../assets/icons/instagram.svg" alt="" class="cursor-pointer"/>
          <img src="../assets/icons/fb.svg" alt="" class="cursor-pointer"/>
        </div>
        <div class="w-full h-[2px] bg-teal-300 absolute bottom-0 right-0"></div>
        <div class="w-[2px] h-[30px] bg-teal-300 absolute bottom-0 right-0"></div>
      </div>
    </div>
  </section>
</template>
