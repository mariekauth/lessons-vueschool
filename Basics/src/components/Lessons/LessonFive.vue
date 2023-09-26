<script setup>
import { ref } from 'vue'

const text = ref('')
const done = ref(true);
const ui = ref('');

function onInput(e) {
  text.value = e.target.value
}
</script>
<template>
  <input :value="text" @input="onInput" placeholder="Type here">
  <input v-model="text" placeholder="Type here">
  <p>{{ text }}</p>
  <input type="checkbox" v-model="done" /> <label><strong>Checked:</strong> {{ done }}</label>
  <br />
  <label>Select an option: </label>
  <select v-model="ui">
    <option value=""></option>
    <option value="Angular">Angular</option>
    <option value="React">React</option>
    <option value="Vue">Vue</option>
  </select>
  <br />
  <label>UI Selection: </label><span>{{ ui }}</span>
  <p>The first input uses value and @input with a function to handle two way binding. 
    The second input uses v-model to accomplish the same thing (without the need to call a function).
    Both inputs are bound to the same reference.
  </p>
  <p>The checkbox and dropdown also use two way binding.</p>
</template>
<style scoped>
 input {margin-right: 5px;}
 select {margin-right: 5px;}
</style>