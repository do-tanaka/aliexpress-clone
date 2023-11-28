<script setup lang="ts">
const enableCustomLayout = () => {
  setPageLayout('custom')
}
</script>
<template>
  <div>
    <button @click="enableCustomLayout">Update layout</button>
    <h1>Main Page</h1>
  </div>
</template>
