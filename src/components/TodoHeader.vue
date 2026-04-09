<script setup>
import { RouterLink } from 'vue-router';
</script>
 
<template>
  <header>
    <nav class="container">
      <div class="branding">
        <img src="../assets/Vue_Logo_Black.png" alt="Vue Logo" />
        <h1>Todo App</h1>
      </div>

      <ul class="nav-routes">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss" scoped>

</style>