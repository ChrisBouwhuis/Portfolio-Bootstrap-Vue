<script setup>
const props = defineProps({
  to: {
    default: '/',
    type: String,
    required: true
  }
})
</script>

<template>
  <router-link :to="props.to" class="btn btn-primary hoverEffect m-1">
    <slot></slot>
  </router-link>
</template>

<style scoped>
.hoverEffect {
  transition: all 0.3s;
}

.hoverEffect:hover {
  transform: scale(1.1);
  background: linear-gradient(45deg, hsla(168, 85%, 52%, 0.5), hsla(263, 88%, 45%, 0.5) 100%);
  color: black;
}
</style>
