<template>
  <div class="container">
    <Header />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Header from '../../components/Header/index.vue'
import Contact from '../../components/Contact/index.vue'
import Footer from '../../components/Footer/index.vue'

export default {
  components: {
    Header,
    Contact,
    Footer
  }
}
</script>

<style scoped>

</style>