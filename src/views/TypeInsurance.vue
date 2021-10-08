<template>
  <div class="Home">
    <TypeInsurance />
    <SocialPage />
    <FooterPage />
  </div>
</template>


<script>

import TypeInsurance from "@/components/TypeInsurance.vue";
import SocialPage from "@/components/SocialPage.vue";
import FooterPage from "@/components/FooterPage.vue";

export default {

  name: "Home",
  components: {
    TypeInsurance,
    FooterPage,
    SocialPage

  
  },
  
}
</script>