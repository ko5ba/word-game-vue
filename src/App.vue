<script setup>
import Button from './components/ui/Button.vue';
const dateNow = new Date().toLocaleDateString('ru-RU')
</script>

<template>
  <p>Текущая дата: {{ dateNow }}</p>
  <Button />
</template>

<style scoped>

</style>
