<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <h2>Welcome to my learning hub site</h2>
    <h3>Its me Adil</h3>
  </div>

 
 
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
