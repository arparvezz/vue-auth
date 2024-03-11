<script setup>
import Main from "./components/Main.vue";
import Home from "./components/Home.vue";
import login from "./components/Login.vue";

</script>

<template>
  <div class="container mx-auto">
    <Main/>
    <div class="flex flex-col md:flex-row space-x-3">
      <router-view/>
    </div>
  </div>
   
</template>

<style scoped>

</style>
