<template>
  <v-app>
    <v-app-bar app color="white" elevation="2">
      <v-toolbar-title>
        <v-btn text to="" >
          <h2 class="custom__colour">CTED</h2>
        </v-btn>
      </v-toolbar-title>
      <v-spacer></v-spacer>

      <v-toolbar-items>
        <v-btn flat class="mx-2" to="/about" elevation="0">About</v-btn>

        <v-btn
          flat
          class="white--text"
          color="#0096C7"
          to="/contact"
          elevation="0"
          >Contact Us</v-btn
        >
      </v-toolbar-items>
    </v-app-bar>
    <v-main>
      <router-view></router-view>
      
     
    </v-main>

    <!-- <v-footer padless>
      <v-card flat tile class="text-center" width="100%">
        <v-card-text>
          <div class="mb-7">
            <v-btn class="mx-4" text color="#0096c7" href="#home">
              Home
            </v-btn>
            <v-btn class="mx-4" text color="#0096c7" href="#about">
              About
            </v-btn>
            <v-btn class="mx-4" text color="#0096c7" href="#contact">
              Contact Us
            </v-btn>
          </div>
          <v-btn v-for="icon in icons" :key="icon" class="mx-4" icon color="#5D8099">
            <v-icon size="24px">
              {{ icon }}
            </v-icon>
          </v-btn>
        </v-card-text>
      </v-card>
    </v-footer> -->
  </v-app>
</template>

<script>


export default {
  name: "App",

  components: {
   
  },

  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-google", "mdi-linkedin"],

    //
  }),
};
</script>

<style scoped>
.custom__colour {
  color: #0096c7;
}
</style>
