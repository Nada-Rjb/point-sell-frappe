<template>
  <div class="home"></div>
  <app-search></app-search>
  <customer-info></customer-info>
  <DebtSummary></DebtSummary>
</template>

<script>
import AppSearch from "@/components/HomePage/AppSearch.vue";
import CustomerInfo from "@/components/HomePage/CustomerInfo.vue";
import DebtSummary from "@/components/HomePage/DebtSummary.vue";
export default {
  name: "HomeView",
  components: {
    AppSearch,
    CustomerInfo,
    DebtSummary,
  },
};
</script>
