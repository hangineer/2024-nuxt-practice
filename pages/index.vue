<script setup lang="ts">
const route = useRoute();
</script>

<template>
  <div>
    <h1>Page: index 首頁</h1>
    <div>當前路由: {{ route.fullPath }}</div>
  </div>
</template>

<style scoped></style>
