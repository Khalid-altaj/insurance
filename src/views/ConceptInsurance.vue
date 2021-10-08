<template>
  <div class="concept">
    <ConceptInsurance />
    <SocialPage />
    <FooterPage />
  </div>
</template>


<script>

import ConceptInsurance from "@/components/ConceptInsurance.vue";
import SocialPage from "@/components/SocialPage.vue";
import FooterPage from "@/components/FooterPage.vue";

export default {

  name: "concept",
  components: {
    ConceptInsurance,
    FooterPage,
    SocialPage

  
  },
  
}
</script>