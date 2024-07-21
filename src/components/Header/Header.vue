<template>
  <header class="header">
    <div class="header__inner container">
      <logo class="header__logo" />
      <header-menu />
      <header-actions />
    </div>
  </header>
</template>

<script setup>
import Logo from "@/components/Header/Logo.vue";
import HeaderMenu from "@/components/Header/HeaderMenu.vue";
import HeaderActions from "@/components/Header/HeaderActions.vue";
</script>

<style lang="scss">
@import '@/styles/blocks/header';
</style>
