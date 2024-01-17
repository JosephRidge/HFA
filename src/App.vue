<script setup>
import NavigationBar from './components/NavigationBar.vue'
</script>

<template >
  <header  class=" ">
    <NavigationBar />
  </header>
  <body  class="mx-16 ">
    <RouterView />
  </body>
</template>

<style scoped></style>
