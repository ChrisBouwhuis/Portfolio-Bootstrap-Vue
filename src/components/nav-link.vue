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
  <RouterLink class="nav-item text-white px-2 m-1 nav-link" :to="props.to">
    <slot></slot>
  </RouterLink>
</template>
