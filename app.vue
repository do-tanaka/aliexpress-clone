<script setup lang="ts">
const admin = ref(true)
const layout = admin.value ? 'custom' : 'layout'
</script>

<template>
  <NuxtLayout :name="layout">
    <NuxtPage />
  </NuxtLayout>
</template>
