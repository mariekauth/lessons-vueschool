<script setup>
const props = defineProps({
  msg: String
})

const emit = defineEmits(['response'])

emit('response', 'hello from child')
</script>

<template>
  {{ msg || 'I am a child' }}
</template>
<style scoped>
</style>