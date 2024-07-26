<template>
  <nav>
    <NavigationBar />
  </nav>
  <router-view />
  <footer>
    <FooterBar />
  </footer>
</template>

<script>
import NavigationBar from "./components/NavigationBar.vue";
import FooterBar from "./components/FooterBar.vue"
export default {
  components: {
    NavigationBar,
    FooterBar
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
#app {
  font-family: "Bebas Neue", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #232b33;
  scroll-behavior: smooth;
  scrollbar-color: transparent;
}
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
html::-webkit-scrollbar {
  display: none;
}
html {
  -ms-overflow-style: none;
  scrollbar-width: none;
}
</style>
