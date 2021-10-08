<template>
  <div class="about">
  <AboutPage />
  <SocialPage />
  <FooterPage />
  </div>
</template>



<script>

import AboutPage from "@/components/AboutPage.vue";
import SocialPage from "@/components/SocialPage.vue";
import FooterPage from "@/components/FooterPage.vue";

export default {

  name: "about",
  components: {
    AboutPage,
    FooterPage,
    SocialPage

  
  },
  
}
</script>