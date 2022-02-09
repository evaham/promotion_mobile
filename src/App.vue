<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">본부시스템 안내</router-link>
      <router-link to="/faq">FAQ</router-link>
    </div>
    <router-view />
  </div>
</template>
<style lang="scss">
@import "@/assets/css/common.scss";
// @import '~@/assets/icomoon/style.css';
</style>
