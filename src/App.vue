<template>
  <v-app>
    <v-content>
      <Navbar/>
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',

  data () {

  },
  components: {
    Navbar
  }
}
</script>
