<script setup lang="ts"></script>

<template>
  <header>
    <hr class="blue-line" />
    <h1>The Magnificent Seven Companies</h1>
  </header>
</template>

<style scoped lang="scss">
header {
  padding: 64px 0;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  gap: 24px;

  hr {
    width: 96px;
    height: 32px;
    border-top-right-radius: 16px;
    border-bottom-right-radius: 16px;
    background-color: #39daff;
    border: unset;
  }

  h1 {
    color: white;
    font-size: 36px;
    font-weight: 500;
  }
}
</style>
