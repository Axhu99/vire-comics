<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import { HeaderNavbar, Comics } from './assets/data';
export default {
  name: 'DC',
  components: { AppHeader, AppMain, AppFooter },
  data: () => ({
    HeaderNavbar,
    Comics
  })
};
</script>

<!-- TODO separere e creare i data dove e' possibile fare SCCS -->
<template>
  <AppHeader :navbarLinks="HeaderNavbar" />
  <AppMain :comics="Comics" />
  <AppFooter />
</template>

<style lang="scss">
@use './assets/scss/style.scss';

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>