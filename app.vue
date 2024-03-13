
<template>
  <div class="">
    <HeaderLayout />
    <NuxtPage />
    <FooterLayout />
  </div>
</template>
<script>
import FooterLayout from './layouts/FooterLayout/FooterLayout.vue';
import HeaderLayout from './layouts/HeaderLayout/HeaderLayout.vue';

export default {
  components: {
    HeaderLayout,
    FooterLayout
  }
}
</script>
<!-- src/app.vue -->
<style>
@import 'assets/styles/tailwind.css';
@import 'assets/styles/main.css';
</style>
