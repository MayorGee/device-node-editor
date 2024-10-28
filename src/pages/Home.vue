<template>
  <div class="page">
    <h1 class="page__header">Page Header</h1>    
  </div>
</template>

<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<style scoped>
.page {
  color: green
}
</style>
