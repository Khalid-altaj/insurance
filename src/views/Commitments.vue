<template>
  <div class="Commitments">
    <CommitmentsPage />
    <SocialPage />
    <FooterPage />
  </div>
</template>


<script>

import CommitmentsPage from "@/components/CommitmentsPage.vue";
import SocialPage from "@/components/SocialPage.vue";
import FooterPage from "@/components/FooterPage.vue";

export default {

  name: "Home",
  components: {
    CommitmentsPage,
    FooterPage,
    SocialPage

  
  },
  
}
</script>