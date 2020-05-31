<template>
  <div id="app">
    <TopNav />
    <router-view />
  </div>
</template>

<script>
import TopNav from "./components/TopNav/TopNav";

export default {
  components: {
    TopNav
  }
};
</script>

<style scoped>
</style>
