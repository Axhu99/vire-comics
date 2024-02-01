<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
export default {
  name: 'DC',
  components: { AppHeader, AppMain }
};
</script>

<template>
  <AppHeader />
  <AppMain />
  <footer>
    <section class="footer-top">

    </section>
    <section class="footer-bot">
      <button>SIGN-UP NOW</button>
      <div class="social">

      </div>
    </section>
  </footer>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>