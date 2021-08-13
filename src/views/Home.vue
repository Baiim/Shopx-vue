<template>
  <div class="home">
    <!-- Header -->
    <HeaderShop />
    <HeroShop />
    <BannerShop />
    <InstaShop />
    <PartnerShop />
    <FooterShop />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShop from "@/components/HeaderShop.vue"
import HeroShop from "@/components/HeroShop.vue"
import BannerShop from "@/components/BannerShop.vue"
import InstaShop from "@/components/InstaShop.vue"
import PartnerShop from "@/components/PartnerShop.vue"
import FooterShop from "@/components/FooterShop.vue"

export default {
  name: "Home",
  components: {
    HeaderShop,
    HeroShop,
    BannerShop,
    InstaShop,
    PartnerShop,
    FooterShop,
  },
}
</script>
