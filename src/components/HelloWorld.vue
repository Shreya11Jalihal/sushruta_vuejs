<script setup lang="ts">
import { ref, reactive, onMounted } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div>
  </div>
    
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
