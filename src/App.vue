<template>
  <v-app>
    <v-content>
      <Navbar></Navbar>
      <router-view></router-view>
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