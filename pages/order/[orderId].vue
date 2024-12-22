<script setup>
const route = useRoute();
</script>
<template>
  <div>
    <h1 class="mt-3">預定成功/失敗頁面</h1>
    <h2>{{ `預定編號：${route.params.orderId}` }}</h2>
  </div>
</template>
<style scoped></style>
