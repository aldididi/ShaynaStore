<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenBanner />
    <InstaShayna />
    <PartnerLogo />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import WomenBanner from "@/components/WomenBanner.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import PartnerLogo from "@/components/PartnerLogo.vue";
import Footer from "@/components/FooterShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroShayna,
    WomenBanner,
    InstaShayna,
    PartnerLogo,
    Footer,
  },
};
</script>
