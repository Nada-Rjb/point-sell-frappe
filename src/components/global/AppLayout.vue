<template>
  <div class="layout"></div>
  <div>
    <AppNav></AppNav>
    <slot></slot>
    <main class="content"></main>
  </div>
  <AppFooter></AppFooter>
</template>
<script>
import AppNav from "./AppNav.vue";
import AppFooter from "./AppFooter.vue";

export default {
  data: () => ({}),
  components: {
    AppNav,
    AppFooter,
  },
};
</script>
