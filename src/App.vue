<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import { HeaderNavbar } from './assets/data';
export default {
  name: 'DC',
  components: { AppHeader, AppMain, AppFooter },
  data: () => ({
    HeaderNavbar
  })
};
</script>

<template>
  <AppHeader :navbarLinks="HeaderNavbar" />
  <AppMain />
  <AppFooter />
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>