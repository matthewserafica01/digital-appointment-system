<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1 class="bg-red-500">{{ msg }}</h1>
</template>

<style scoped>
</style>
