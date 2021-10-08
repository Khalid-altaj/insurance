<template>
  <div class="Home">
    <HomePage />
    <FooterPage />
  </div>
</template>


<script>

import HomePage from "@/components/HomePage.vue";
import FooterPage from "@/components/FooterPage.vue";

export default {

  name: "Home",
  components: {
    HomePage,
    FooterPage,

  
  },
  
}
</script>