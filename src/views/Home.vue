<template>
  <div class="home">
    <!-- Page Preloder -->
      <!-- <div id="preloder">
          <div class="loader"></div>
      </div> -->
      <HeaderShayna />
      <HeroShayna />
      <WomanBanner />
      <InstaShayna />
      <PartnerShayna />
      <FooterShayna />

    </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "@/components/HeaderShayna.vue"
import HeroShayna from "@/components/HeroShayna.vue"
import WomanBanner from "@/components/WomanBanner.vue"
import InstaShayna from "@/components/InstaShayna.vue"
import PartnerShayna from "@/components/PartnerShayna.vue"
import FooterShayna from "@/components/FooterShayna.vue"


export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroShayna,
    WomanBanner,
    InstaShayna,
    PartnerShayna,
    FooterShayna
  }
}
</script>
