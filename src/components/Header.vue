<template>
  <header class="header">
    <div class="header__inner container">
      <a href="#" class="header__logo logo">
        <img class="logo__img" src="@/assets/images/logo.svg" alt="logo" width="142" height="32" loading="lazy">
      </a>
      <div class="header__menu menu">
        <nav class="menu__body">
          <ul class="menu__list">
            <li class="menu__item">
              <a href="#" class="menu__link">Home</a>
            </li>
            <li class="menu__item menu__item--parent">
              <a href="#" class="menu__link">Products</a>
              <div class="sub-menu">
                <ul class="sub-menu__list">
                  <li class="sub-menu__item">
                    <a href="#" class="sub-menu__link">ProductProduct#1</a>
                  </li>
                  <li class="sub-menu__item">
                    <a href="#" class="sub-menu__link">Product#2</a>
                  </li>
                  <li class="sub-menu__item">
                    <a href="#" class="sub-menu__link">Product#3</a>
                  </li>
                  <li class="sub-menu__item">
                    <a href="#" class="sub-menu__link">Product#4</a>
                  </li>
                </ul>
              </div>
            </li>
            <li class="menu__item menu__item--parent">
              <a href="#" class="menu__link">Resources</a>
              <div class="sub-menu">
                <ul class="sub-menu__list">
                  <li class="sub-menu__item">
                    <a href="#" class="sub-menu__link">Resources#1</a>
                  </li>
                  <li class="sub-menu__item">
                    <a href="#" class="sub-menu__link">Resources#2</a>
                  </li>
                  <li class="sub-menu__item">
                    <a href="#" class="sub-menu__link">Resources#3</a>
                  </li>
                  <li class="sub-menu__item">
                    <a href="#" class="sub-menu__link">Resources#4</a>
                  </li>
                </ul>
              </div>
            </li>
            <li class="menu__item">
              <a href="#" class="menu__link">Pricing</a>
            </li>
          </ul>
        </nav>
      </div>
      <div class="header__action action-header">
        <a href="#" class="action-header__avatar avatar">
          <img class="avatar__img" src="@/assets/images/avatar/01.jpg" alt="avatar">
        </a>
        <button class="action-header__icon icon-menu" type="button"><span></span></button>
      </div>
    </div>
  </header>
</template>

<style lang="scss">
@import '@/styles/blocks/header';
</style>