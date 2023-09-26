<script setup>
import { ref } from 'vue'
import ChildComp from './ChildComp.vue'

const msg = ref('from parent')
</script>

<template>
  <ChildComp>This was setup using slots, there is more than covered in the tutorial.</ChildComp>
</template>
<style scoped>
</style>