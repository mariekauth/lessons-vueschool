<script setup>
import { ref } from 'vue'
import ChildComp from './ChildComp.vue'

const greeting = ref('Hello from parent')
</script>

<template>
  <ChildComp msg="greeting" />
  <p>The exercise here get harder to see when they work. I set this solution up using child components.</p>
</template>
<style scoped>
</style>