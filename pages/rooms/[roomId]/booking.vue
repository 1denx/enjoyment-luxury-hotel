<script setup>
const route = useRoute();
</script>
<template>
  <div>
    <h1 class="mt-3">{{ `房型預約:${route.params.roomId}` }}</h1>
  </div>
</template>
<style scoped></style>
