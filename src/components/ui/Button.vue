<script setup></script>

<template>
  <button class="btn">
    Начать игру
  </button>
</template>

<style scoped>
.btn {
  width: 335px;
  height: 68px;
  border-radius: 100px; 
  padding: 16px 10px;
  background-color: var(--color-primary-button);
  color: white;
  font-size: 24px;
  line-height: 36px;
  font-weight: 400; 
  border: none;
  cursor: pointer;
  transition: background-color 0.2s;
}

.btn:hover {
  background-color: var(--color-primary-button-hover);
}
</style>
