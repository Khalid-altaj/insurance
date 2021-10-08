<template>
  <div class="Home">
    <ContactUs />
    <SocialPage />
    <FooterPage />
  </div>
</template>


<script>

import ContactUs from "@/components/ContactUs.vue";
import SocialPage from "@/components/SocialPage.vue";
import FooterPage from "@/components/FooterPage.vue";

export default {

  name: "Home",
  components: {
    ContactUs,
    FooterPage,
    SocialPage

  
  },
  
}
</script>