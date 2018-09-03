<template>
  <div>
    <Header/>
    <div class="container-fluid pt-3 pb-5">
      <div class="row">
        <nuxt/>
        <OrderCart/>
      </div>
    </div>
    <Footer/>
  </div>
</template>
<script>
import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'
import OrderCart from '~/components/OrderCart.vue'
export default {
  components: {
    Header,
    Footer,
    OrderCart
  }
}
</script>

<style lang="scss">
@import "../assets/all";
</style>

