<template>
  <div class="container">
    <Header />
    <Map />
    <Footer />
  </div>
</template>

<script>
import Header from '../../components/Header/index.vue'
import Map from '../../components/Map/index.vue'
import Footer from '../../components/Footer/index.vue'

export default {
  components: {
    Header,
    Map,
    Footer
  }
}
</script>

<style scoped>

</style>