<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header> 
      <nav class="my-4 mx-16 ">
        <RouterLink class="hover:cursor-pointer hover:bg-green-100 mr-2 text-xl px-2 py-1 rounded-md" to="/">Home</RouterLink>
        <RouterLink class="hover:cursor-pointer hover:bg-green-100 mr-2 text-xl px-2 py-1 rounded-md" to="/about">Maps</RouterLink>
      </nav> 
      <hr class="mb-10"/>
  </header>

</template>

<style scoped></style>
