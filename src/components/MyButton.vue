<script setup>
const props = defineProps({
    text: String
});
</script>

<template>
  <button
    class="flex gap-5 justify-center items-center px-12 py-4 md:px-20 md:py-5 w-max bg-cyan-500 rounded-[48px] relative m-auto md:m-0"
  >
    <span class="uppercase text-[14px] font-bold tracking-[2.1px]">{{text}}</span>
    <div
      class="z-10 my-auto w-9 h-0.5 bg-white rounded-2xl absolute top-[50%] translate-y-[-50%] right-[-18px]"
      aria-hidden="true"
    ></div>
  </button>
</template>

<style scoped>
button {
  box-shadow: 5px 15px 40px 0px rgba(0, 201, 224, 0.2);
}
</style>
