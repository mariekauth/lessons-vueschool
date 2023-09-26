<script setup>
import { ref, onMounted } from 'vue'

const pElementRef = ref(null)

onMounted(() => {
  pElementRef.value.textContent = 'mounted'
})
</script>

<template>
  <p ref="pElementRef">hello</p>
  <p>When you have dynamic content that is being loaded from a backend, you may need the onMounted method.</p>
  <p>See <a href="https://vuejs.org/guide/essentials/lifecycle.html#lifecycle-diagram" target="_blank">the Lifecycle guide</a> for more information</p>
</template>
<style scoped>
</style>