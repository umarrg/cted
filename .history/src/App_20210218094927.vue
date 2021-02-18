<template>
  <v-app>
    <v-app-bar flat app color="white" >
      <v-toolbar-title>
        <v-btn text to="/" tile color="white">
          <h2 class="custom__colour">CTED</h2>
        </v-btn>
      </v-toolbar-title>
      <v-spacer></v-spacer>

      <v-toolbar-items>
        <!-- <v-btn tile class="mx-2" to="/about" elevation="0">About</v-btn> -->

        <v-btn
          tile
          class="white--text"
          color="#fcaf2f"
          to="/contact"
          elevation="0"
          >Contact Us</v-btn
        >
      </v-toolbar-items>
    </v-app-bar>
          <!-- <v-divider></v-divider> -->

    <v-main>
      <router-view></router-view>
      
           


    </v-main>

   
  </v-app>
</template>

<script>



export default {
  name: "App",

  components: {
   
  },

  data: () => ({
  

    //
  }),
};
</script>

<style scoped>
.custom__colour {
  color: #845b79;
}
</style>
