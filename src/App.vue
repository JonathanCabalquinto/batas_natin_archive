<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <a href="https://batasnatin.com/about-us.html">
  <h2 class="text-6xl font-black"> BATASNATIN ARCHIVE</h2>  

    <div class="flex align-middle items-center">
    <img src="/src/assets/logo.png" alt="batas natin" height="50" width="50">
     <div class="w-full pt-1">
    <div class="w-full h-10 text-xs flex ml-2  rounded bg-gray-200">
      <div style="width: 10%" class="rounded-l-md shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-gray-500">10%</div>
    </div>
  </div>
 </div>
  <h2 class="text-2xl font-semibold"> From here, we we move forward!...</h2>  
  </a>
</template>