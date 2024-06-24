<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav class="navbar bg-primary text-secondary">
        <router-link to="/" class="navbar-brand">
          <svg width="40" height="20" xmlns="http://www.w3.org/2000/svg">
            <svg height="30" width="200" xmlns="http://www.w3.org/2000/svg">
              <text x="10" y="15" fill="white">C</text>
              <text x="21" y="15" fill="white">B</text>
              <line x1="8" y1="18" x2="34" y2="18" style="stroke: white; stroke-width: 2" />
            </svg>
          </svg>
        </router-link>
        <RouterLink to="/" class="nav-item text-white">Home</RouterLink>
        <RouterLink to="/about" class="nav-item text-white">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped></style>
