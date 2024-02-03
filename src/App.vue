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

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  max-width: 1400px;
  margin: 0 auto;
}

/* img {
  max-width: 100%;
  height: auto;
} */
</style>