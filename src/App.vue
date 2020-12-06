<template>
  <v-app class="grey lighten-4">
    <v-content>
      <Navbar></Navbar>
      <router-view/>
      <Footer></Footer>
    </v-content>
  </v-app>
</template>

<script>
  import Navbar from './components/Navbar.vue'
  import Footer from './components/Footer.vue'

  export default {
    components: {
      Navbar,
      Footer
    }
  }
</script>