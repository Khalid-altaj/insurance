<template>
  <div class="Contract">
    <ContractPage />
    <SocialPage />
    <FooterPage />
  </div>
</template>


<script>

import ContractPage from "@/components/ContractPage.vue";
import SocialPage from "@/components/SocialPage.vue";
import FooterPage from "@/components/FooterPage.vue";

export default {

  name: "Contract",
  components: {
    ContractPage,
    FooterPage,
    SocialPage

  
  },
  
}
</script>