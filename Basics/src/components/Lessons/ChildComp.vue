<script setup>
const props = defineProps({
  msg: String
})
</script>

<template>
  {{ msg || 'I am a child' }}
</template>
<style scoped>
</style>