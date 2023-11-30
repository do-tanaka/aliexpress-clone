<script setup lang="ts">
const { count, inc, dec } = useCounter(5)
</script>

<template>
  <div>
    <h1>Main Page</h1>
    <button @click="() => inc()">+</button>
    <button @click="() => dec()">-</button>
    <div>{{ count }}</div>
  </div>
</template>
