<script setup>
import { RouterLink, RouterView } from 'vue-router'
import NavLink from '@/components/nav-link.vue'
</script>

<template>
  <header>
    <div class="wrapper mb-5 p-2">
      <nav class="navbar bg-primary text-secondary fixed-top">
        <div class="container">
          <router-link to="/" class="navbar-brand p-1">
            <svg width="40" height="20" xmlns="http://www.w3.org/2000/svg">
              <svg height="30" width="200" xmlns="http://www.w3.org/2000/svg">
                <text x="10" y="15" fill="white">C</text>
                <text x="21" y="15" fill="white">B</text>
                <line x1="8" y1="18" x2="34" y2="18" style="stroke: white; stroke-width: 2" />
              </svg>
            </svg>
          </router-link>
          <div class="navbar-nav flex flex-row">
            <nav-link to="/">Home</nav-link>
            <nav-link to="/about">About</nav-link>
            <nav-link to="/projects">Projects</nav-link>
            <nav-link to="/contact">Contact</nav-link>
          </div>
        </div>
      </nav>
    </div>
  </header>

  <RouterView />

  <footer class="bg-primary text-secondary fixed-bottom">
    <div class="container">
      <p class="text-center p-2">© 2024 Chris Bouwhuis</p>
    </div>
  </footer>
</template>

<style scoped></style>
