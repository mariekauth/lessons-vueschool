<script setup>
</script>
<template>
    <div class="item">
      <div class="details">
        <h3>
          <slot name="heading"></slot>
        </h3>
        <div class="lesson">
          <slot name="lesson"></slot>
        </div>
        <slot></slot>
      </div>
    </div>
  </template>
<style scoped>
</style>