<script setup>
const route = useRoute();
const router = useRouter();
</script>

<template>
  <div>
    <h1 class="mt-3">房型詳細頁面 {{ route.fullPath }}</h1>
    <button type="button" class="btn btn-dark" @click="router.go(-1)">
      回上一頁
    </button>
  </div>
</template>

<style></style>
