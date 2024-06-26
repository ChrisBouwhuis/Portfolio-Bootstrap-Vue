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
  <RouterLink class="nav-item px-2 m-1 nav-link hover" :to="props.to">
    <slot></slot>
  </RouterLink>
</template>

<style scoped>
.hover {
  color: white;
  transition: all 0.3s;
}

.hover:hover {
  transform: scale(1.1);
  color: #e2e2d5;
}
</style>
