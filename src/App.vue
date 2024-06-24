<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav class="navbar bg-primary text-secondary">
        <router-link to="/" class="navbar-brand"><i class=""></i></router-link>
        <RouterLink to="/" class="nav-item">Home</RouterLink>
        <RouterLink to="/about" class="nav-item">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>



</style>
