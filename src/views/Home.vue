<template>
  <div class="home">
    <HeaderSnaptex />
    <HeroSnaptex />
    <WomanBannerSnaptex />
    <InstaSnaptex />
    <PartnerSnaptex />
    <FooterSnaptex />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderSnaptex from "@/components/HeaderSnaptex.vue";
import HeroSnaptex from "@/components/HeroSnaptex.vue";
import WomanBannerSnaptex from "@/components/WomanBannerSnaptex.vue";
import InstaSnaptex from "@/components/InstaSnaptex.vue";
import PartnerSnaptex from "@/components/PartnerSnaptex.vue";
import FooterSnaptex from "@/components/FooterSnaptex.vue";

export default {
  name: "Home",
  components: {
    // HelloWorld
    HeaderSnaptex,
    HeroSnaptex,
    WomanBannerSnaptex,
    InstaSnaptex,
    PartnerSnaptex,
    FooterSnaptex
  }
};
</script>
