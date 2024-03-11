<script setup>

</script>
<template>
  
  <div class="container">
    <div class="container mx-auto">
      <div class="my-4">
        <h2 class="text-xl">
          Vue Supremacy
        </h2>
      </div>
      <nav class="space-x-3">
        <!-- <a class="no-underline" href="/">Home</a>
        <a class="no-underline" href="/">About</a>
        <a class="no-underline" href="/">Login</a>
        <a class="no-underline" href="/">Secret</a> -->
        <router-link class="no-underline" to="/">Home</router-link>
        <router-link class="no-underline" to="/about">About</router-link>
        <router-link class="no-underline" to="/login">Login</router-link>
        <router-link class="no-underline" to="/secret">Secret</router-link>
      </nav>
      
    </div>
  </div>
</template>
<style></style>
