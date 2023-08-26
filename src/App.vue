<template>
  <Navbar :logo="logo_src" :alt="app_name" />
  <div>
    <router-view />
  </div>
  <Footer />
</template>

<script>
import Footer from './components/Footer.vue';
import Navbar from './components/Navbar.vue';
import './reset.scss';

export default {
  components: {
    Navbar,
    Footer
  },
  data() {
    return {
      logo_src: "/img/logo.png",
      app_name: "burgShop"
    }
  }
}
</script>

<style>
body {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

h1 {
  text-align: center;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 40px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  margin: 40px;
}

.main-container {
  padding-top: 100px;
  padding-bottom: 120px;
}
</style>
