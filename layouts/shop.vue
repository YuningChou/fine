<template>
  <div>
    <Header/>
      <nuxt/>
      <Feature/>
    <Footer/>
  </div>
</template>
<script>
import Header from '~/components/sHeader.vue'
import Footer from '~/components/sFooter.vue'
import Feature from '~/components/Feature.vue'
export default {
  components: {
    Header,
    Footer,
    Feature
  }
}
</script>

<style lang="scss">
@import "../assets/all";
</style>

