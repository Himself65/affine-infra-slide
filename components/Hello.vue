<template>
  <div>
    Hello {{ text }}!
  </div>
</template>

<script setup>
import { ref } from 'vue'

const text = ref('World')
</script>

<style scoped>

</style>
