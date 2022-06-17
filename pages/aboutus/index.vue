<template>
  <div class="container">
    <Header />
    <AboutUs />
    <Footer />
  </div>
</template>

<script>
import Header from '../../components/Header/index.vue'
import AboutUs from '../../components/AboutUs/index.vue'
import Footer from '../../components/Footer/index.vue'

export default {
  components: {
    Header,
    AboutUs,
    Footer
  }
}
</script>

<style scoped>

</style>