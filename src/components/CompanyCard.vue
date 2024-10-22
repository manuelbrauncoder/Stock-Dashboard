<script setup lang="ts"></script>
<template>
  <div class="card">
    <div class="company">
      <img src="@/assets/img/logo-apple.svg" alt="logo" />
      <h3>Apple</h3>
    </div>
    <span class="quartal">Revenue Q1 2024</span>
    <div class="data">
      <h2>38.52</h2>
      <div class="percentage">
        <span>+1.06</span>
        <span>2.83%</span>
      </div>
    </div>
    <span class="currency"> in Bill USD </span>
  </div>
</template>
<style lang="scss">
@use '@/assets/base.scss' as *;

.card {
  background-color: #011f35;
  border-radius: 16px;
  padding: 20px 24px;
  display: flex;
  gap: 8px;
  flex-direction: column;
  .company {
    display: flex;
    align-items: center;
    gap: 8px;
    img {
      width: 20px;
      height: 20px;
    }
    h3 {
      font-size: 20px;
      font-weight: 500;
    }
  }
  .quartal {
    font-size: 12px;
    font-weight: 400;
  }
  .data {
    display: flex;
    gap: 4px;
    h2 {
      font-weight: 24px;
      font-weight: 500;
    }
    .percentage {
      display: flex;
      flex-direction: column;
      span {
        font-size: 13px;
        font-weight: 500;
        color: $color-green;
      }
    }
  }
  .currency {
    font-size: 8px;
    font-weight: 400;
  }
}
</style>
