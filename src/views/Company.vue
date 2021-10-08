<template>
  <div class="Home">
    <CompanyPage />
    <SocialPage />
    <FooterPage />
  </div>
</template>


<script>

import CompanyPage from "@/components/CompanyPage.vue";
import SocialPage from "@/components/SocialPage.vue";
import FooterPage from "@/components/FooterPage.vue";

export default {

  name: "Home",
  components: {
    CompanyPage,
    FooterPage,
    SocialPage

  
  },
  
}
</script>