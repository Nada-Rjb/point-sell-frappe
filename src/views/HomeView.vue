<template>
  <div class="home"></div>
  <app-search></app-search>
  <customer-info></customer-info>
</template>

<script>
import AppSearch from "@/components/HomePage/AppSearch.vue";
import CustomerInfo from "@/components/HomePage/CustomerInfo.vue";
export default {
  name: "HomeView",
  components: {
    AppSearch,
    CustomerInfo,
  },
};
</script>
