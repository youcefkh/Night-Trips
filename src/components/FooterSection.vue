<script lang="ts" setup></script>

<template>
  <footer
    class="flex flex-col gap-5 items-center justify-between max-w-full w-full max-md:flex-wrap bg-[#011627] px-5 lg:px-80 py-20"
  >
    <div class="flex flex-col lg:flex-row gap-5 justify-between">
      <div class="px-5 max-md:max-w-full">
        <div class="flex gap-5 max-md:flex-col max-md:gap-0 max-md:">
          <div class="flex flex-col w-3/12 max-md:ml-0 max-md:w-full">
            <div
              class="flex flex-col text-base text-white whitespace-nowrap max-md:mt-10"
            >
              <div class="text-lg font-bold uppercase">About</div>
              <img
                loading="lazy"
                src="../assets/icons/arrow.svg"
                class="mt-6 w-14 aspect-[7.69]"
              />
              <a href="#" class="mt-6">Our Mission</a>
              <a href="#" class="mt-7">Terms</a>
              <a href="#" class="mt-6">Copyrights</a>
            </div>
          </div>
          <div class="flex flex-col ml-5 w-3/12 max-md:ml-0 max-md:w-full">
            <div
              class="flex flex-col grow text-base text-white whitespace-nowrap max-md:mt-10"
            >
              <div class="text-lg font-bold uppercase">FAQ</div>
              <img
                loading="lazy"
                src="../assets/icons/arrow.svg"
                class="mt-6 w-14 aspect-[7.69]"
              />
              <a href="#" class="mt-6">Rules</a>
              <a href="#" class="mt-7">Tickets</a>
              <a href="#" class="mt-6">Editions</a>
              <a href="#" class="mt-6">Contribute</a>
            </div>
          </div>
          <div class="flex flex-col ml-5 w-3/12 max-md:ml-0 max-md:w-full">
            <div
              class="flex flex-col grow text-base text-white whitespace-nowrap max-md:mt-10"
            >
              <div class="text-lg font-bold uppercase">Events</div>
              <img
                loading="lazy"
                src="../assets/icons/arrow.svg"
                class="mt-6 w-14 aspect-[7.69]"
              />
              <a href="#" class="mt-6">Star Gazing</a>
              <a href="#" class="mt-6">Desert Mania</a>
              <a href="#" class="mt-6">Dunes Madness</a>
              <a href="#" class="mt-6">Spooky Land</a>
            </div>
          </div>
          <div class="flex flex-col ml-5 w-3/12 max-md:ml-0 max-md:w-full">
            <div class="flex flex-col text-base text-white max-md:mt-10">
              <div class="text-lg font-bold uppercase whitespace-nowrap">
                Contact us
              </div>
              <img
                loading="lazy"
                src="../assets/icons/arrow.svg"
                class="mt-6 w-14 aspect-[7.69]"
              />
              <a href="#" class="mt-6">hello@example.com</a>
              <a href="#" class="mt-6">(405) 555-0128</a>
              <a href="#" class="mt-6">(252) 555-0126</a>
            </div>
          </div>
        </div>
      </div>
      <div
        class="flex flex-col self-start px-5 text-lg font-bold text-white uppercase whitespace-nowrap basis-0"
      >
        <div>Follow us</div>
        <img
          loading="lazy"
          src="../assets/icons/arrow.svg"
          class="mt-6 w-14 aspect-[7.69]"
        />
        <div class="flex gap-5 mt-5 pr-5">
          <img src="../assets/icons/twitter.svg" alt="" class="cursor-pointer"/>
          <img src="../assets/icons/instagram.svg" alt="" class="cursor-pointer"/>
          <img src="../assets/icons/fb.svg" alt="" class="cursor-pointer"/>
        </div>
      </div>
    </div>

    <div class="text-base leading-6 text-center text-white max-w-[309px] my-20">
      Copyright © Night Trips 2019. All rights reserved.
    </div>
    <h1 class="text-4xl font-bold text-white leading-[68.4px] max-w-[57px]">
      NT<span class="text-teal-300">.</span>
    </h1>
  </footer>
</template>
