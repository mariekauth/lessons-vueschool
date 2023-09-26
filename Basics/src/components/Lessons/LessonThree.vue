<script setup>
import { ref } from 'vue'

const titleClass = ref('title')
const red = (() => {titleClass.value = 'title-red'})
const blue = (() => {titleClass.value = 'title-blue'})
const green = (() => {titleClass.value = 'title-green'})
const reset = (() => {titleClass.value = 'title'})
</script>
<template>
  <h1 :class="titleClass">Make me red</h1> <!-- add dynamic class binding here -->
  <button @click="red">Red</button><button @click="blue">Blue</button><button @click="green">Green</button><button @click="reset">Reset</button>
</template>
<style scoped>
.title {
  color: inherit;
}
.title-red {
  color: red;
}
.title-blue {
  color: blue;
}
.title-green {
  color: green;
}

button {
    margin-right: 5px;
}
</style>