<template>
  <div class="header__action action-header">
    <a href="#" class="action-header__avatar avatar">
      <img class="avatar__img" src="../../assets/images/avatar/01.jpg" alt="avatar">
    </a>
    <button
        type="button"
        class="action-header__icon icon-menu"
        @click="onClickMenu"
    >
      <span></span>
    </button>
  </div>
</template>

<script setup>
const onClickMenu = () => {
  document.body.classList.toggle('menu-open');
}
</script>
