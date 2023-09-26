<script setup>
  import { ref, reactive } from 'vue'
  const defaultMessage = 'Make me dynamic!';
  const message = ref('Make me dynamic!');
  const counter = reactive({ count: 0 })
  
  const changeMessage = (() => {
    message.value = 'I am dynamic!';
  });

  const resetMessage = (() => {
    message.value = defaultMessage;
    counter.count = 0;
  });

  const increment = (() => {
    counter.count++;
  })

  const reduce = (() => {
    counter.count--;
  })
</script>
<template>
   <h1>{{ message }}</h1>
   <h2>Counter: {{ counter.count }}</h2>
   <button @click="increment">Increment</button>
   <button @click="reduce">Reduce</button>
   <button v-if="message === 'Make me dynamic!'" @click="changeMessage">Change Message</button>
   <button v-else @click="resetMessage">Reset</button>
   <br /><br />
   <label>Backwards Message: </label><span>{{ message.split('').reverse().join('') }}</span>
</template>
<style scoped>
  button {
    margin-right: 5px;
  }
</style>