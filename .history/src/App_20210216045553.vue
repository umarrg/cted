<template>
  <v-app>
    <v-app-bar app color="white">
      <v-toolbar-title><h2 class="custom__colour">CTED</h2></v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn class="mx-4" text color="">
        <span class="mr-2">ABOUt</span>
      </v-btn>

      <v-btn class="white--text" color="#0096C7">
        <span class="mr-2">ABOUT</span>
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view></router-view>
    </v-main>
    </
    
  </v-app>
</template>

<script>
import  Footer from  './components/footer';
export default {
  name: "App",

  components: {
    Footer
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
