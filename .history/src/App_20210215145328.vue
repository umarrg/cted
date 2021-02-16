<template>
  <v-app>
    <Navbar/>
    <v-main> </v-main>
  </v-app>
</template>

<script>
import Navbar from '../src/'
export default {
  name: "App",

  components: {
    Navbar
  },

  data: () => ({
    //
  }),
};
</script>
