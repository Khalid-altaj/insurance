<template>
  <div class="WhatInsurance">
    <WhatInsurance />
    <SocialPage />
    <FooterPage />
  </div>
</template>


<script>

import WhatInsurance from "@/components/WhatInsurance.vue";
import SocialPage from "@/components/SocialPage.vue";
import FooterPage from "@/components/FooterPage.vue";

export default {

  name: "Home",
  components: {
    WhatInsurance,
    FooterPage,
    SocialPage

  
  },
  
}
</script>