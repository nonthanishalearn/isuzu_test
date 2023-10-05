<script setup lang="ts">
// import TheWelcome from '../components/TheWelcome.vue'
import Basgetball from '@/assets/images/basgetball.png';
import Hokky from '@/assets/images/hokky.png';

</script>

<template>
  <div class="w-screen h-screen border-2 border-black-600">
    <div class="flex flex-row">
      <img class="absolute w-[400px] p-5  sm:left-0 md:-left-40 xl:left-0" :src="Hokky" alt="Hokky">
      <div class="w-full text-right pt-[500px] md:pt-0">
        <div class="py-10 text-5xl  px-36 text-slate-300">
          ATHLETS
        </div>
        <div class="py-10 text-2xl  px-36 text-slate-300">
          CONNECTION
        </div>
        <div class=" text-2xl text-slate-300 bg-[#F5F4F9]  px-36 py-10">
          COLLABORATION
        </div>
        <div class=" text-2xl text-slate-300 bg-[#5E3DB3]  px-36 py-10">
          GROWTH
        </div>
      </div>
    </div>
    <div class="flex flex-row sm:flex-col">
      <div class="justify-end w-full text-left pt-96 md:pt-0">
        <div class="py-10 text-5xl px-36 text-slate-300">
          PLAYERS
        </div>
        <div class="py-10 text-2xl px-36 text-slate-300">
          CONNECTION
        </div>
        <div class=" text-2xl text-slate-300 bg-[#F5F4F9] px-36 py-10 ">
          COLLABORATION
        </div>
        <div class=" text-2xl text-slate-300 bg-[#090C35] py-10 px-36">
          GROWTH
        </div>
      </div>
      <img class="absolute w-[500px] p-5 sm:right-0 md:-right-52 xl:right-0" :src="Basgetball" alt="Hokky">
    </div>
  </div>
</template>
