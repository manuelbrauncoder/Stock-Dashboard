<script setup lang="ts">
import CompanyCard from './CompanyCard.vue'
</script>
<template>
  <div class="cards">
    <CompanyCard />
    <CompanyCard />
    <CompanyCard />
    <CompanyCard />
    <CompanyCard />
    <CompanyCard />
    <CompanyCard />
  </div>
</template>
<style lang="scss">
.cards {
  display: flex;
  gap: 24px;
  flex-wrap: wrap;
  background-color: #023a62;
  border-radius: 20px;
  padding: 24px;
  width: fit-content;
}
</style>
