<script setup></script>

<template>
  <div
    class="flex flex-col grow p-12 w-full text-white rounded-md shadow-xl bg-[#02223B] max-md:px-5 max-md:mt-6 max-md:max-w-full card"
  >
    <div class="flex gap-5 justify-between items-start mt-6 text-lg leading-9">
      <img
        loading="lazy"
        src="../assets//icons/quotes.svg"
        class="w-8 aspect-[1.28] fill-teal-300"
      />
      <div class="flex-auto mt-2.5">
        <span class="font-bold">
          Elementum mi felis, sit velit lobortis ultricies non. Mattis enim,
          nisl
        </span>
        <br />
        <span class="font-light">
          adipiscing natoque diam et. Cum posuere in velit massa sagittis augue
          egestas. Eu sollicitudin et quam eu. Nunc, sed imperdiet blandit
          morbi. Maecenas lobortis tristique rutrum.
        </span>
      </div>
    </div>
    <div
      class="flex gap-4 self-center mt-9 text-xs font-bold tracking-widest leading-5 uppercase"
    >
      <img
        loading="lazy"
        src="../assets/img/card-img.png"
        class="w-20 aspect-square"
      />
      <div class="my-auto">
        Judy ROSELESS
        <br />
        MARKETING HEAD at ROM.
      </div>
    </div>
  </div>
</template>

<style scoped>
.card {
    box-shadow: 0px 20px 30px 0px rgba(0, 201, 224, 0.03);
}
</style>
