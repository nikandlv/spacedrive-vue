<template>
  <div>
    <header-section />
    <search-section />
    <features-section />
    <why-section />
    <services-section />
    <highlight-section />
  </div>  
</template>
<script>
import HeaderSection from '../layouts/HeaderSection'
import SearchSection from '../layouts/SearchSection'
import FeaturesSection from '../layouts/FeaturesSection'
import WhySection from '../layouts/WhySection'
import ServicesSection from '../layouts/ServicesSection'
import HighlightSection from '../layouts/HighlightSection'
export default {
  components:{
    HeaderSection,
    SearchSection,
    FeaturesSection,
    WhySection,
    ServicesSection,
    HighlightSection
  }

}
</script>
