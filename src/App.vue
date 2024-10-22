<script setup lang="ts">
import { RouterView } from 'vue-router'
import HeaderTop from './components/HeaderTop.vue'
</script>

<template>
  <HeaderTop class="header" />

  <RouterView class="router-view" />
</template>

<style scoped lang="scss"></style>
