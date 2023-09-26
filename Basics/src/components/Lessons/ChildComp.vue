<script setup>
const props = defineProps({
  msg: String
})

const emit = defineEmits(['response'])

emit('response', 'hello from child')
</script>

<template>
  <slot>{{ msg || 'I am a child' }}</slot>
</template>
<style scoped>
</style>