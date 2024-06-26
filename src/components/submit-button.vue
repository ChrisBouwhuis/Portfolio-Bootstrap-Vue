<script setup></script>

<template>
  <button type="submit" class="btn btn-primary hoverEffect m-1">
    <slot></slot>
  </button>
</template>

<style scoped>
.hoverEffect {
  transition: all 0.3s;
}

.hoverEffect:hover {
  transform: scale(1.1);
  background: linear-gradient(45deg, hsla(112, 85%, 52%, 0.5), hsla(198, 88%, 45%, 0.5) 100%);
  color: black;
}
</style>
