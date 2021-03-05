<template>
  <div>
    <Header />
    <Nuxt />
    <!-- <Footer /> -->
  </div>
</template>

<script>
import Header from '~/components/layout/header.vue'
// import Footer from '~/components/layout/footer.vue'

export default {
  components: {
    Header,
    // Footer,
  }
}
</script>