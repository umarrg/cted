<template>
  <v-app>
   

    <v-main>
      <router-view></router-view>
    </v-main>

  </v-app>
</template>

<script>
import Navbar from '../src/components/Navbar'
export default {
  name: "App",

  components: {
    Navbar,
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
.custom__colour {
  color: #0096c7;
}
</style>
