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
};
</script>

<template>
  <Header />
  <Main />
  <Portfolio />
</template>

<style lang="scss" scoped></style>
