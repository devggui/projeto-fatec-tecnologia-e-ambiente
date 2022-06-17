<template>
  <div class="container">
    <Header />
    <HomeContent />
    <Footer />
  </div>
</template>

<script>
import Header from '../components/Header/index.vue'
import HomeContent from '../components/HomeContent/index.vue'
import Footer from '../components/Footer/index.vue'

export default {
  components: {
    Header,
    HomeContent,
    Footer,
  }
}
</script>
