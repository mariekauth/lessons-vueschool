<script setup>
import { ref } from 'vue'

const count = ref(0)

function increment() {
  // update component state
  count.value++
}

function reset() {
  count.value = 0;
}
</script>
<template>
  <!-- make this button work -->
  <button @click="increment">count is: {{ count }}</button>
  <button @click="reset" v-if="count > 0">Reset</button>
  <br />
  Notice how this count is separate from the counter in lesson 2 due to scope.
</template>
<style scoped>
button {
  margin-right: 5px;
}
</style>