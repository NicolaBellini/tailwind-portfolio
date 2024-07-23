<script>
import Main from "./components/main.vue";
import Header from "./components/header.vue";
import Portfolio from "./components/portfolio.vue";
export default {
  components: {
    Header,
    Main,
    Portfolio,
  },
  data() {
    return {
      darkMode: false,
    };
  },
  methods: {
    toggleDarkMode() {
      this.darkMode = !this.darkMode;
      console.log(this.darkMode);
    },
  },
};
</script>

<template>
  <div :class="darkMode ? 'dark' : ''">
    <Header @darkMode="toggleDarkMode" />
    <Main />
    <Portfolio />
  </div>
</template>

<style lang="scss" scoped></style>
