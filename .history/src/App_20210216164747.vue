<template>
  <v-app>
    <v-app-bar app color="white" elevation="3">
      <v-toolbar-title><h2 class="custom__colour">CTED</h2></v-toolbar-title>
      <v-spacer></v-spacer>

      <v-toolbar-items>
        <v-btn flat class="mx-2" to=""
          >About</v-btn
        >

        <v-btn flat class="white--text" color="#0096C7">Contact Us</v-btn>
      </v-toolbar-items>
    </v-app-bar>
    <v-main>
      <Home />
      <HERO />
      <Work />

      <Talk />
    </v-main>
  </v-app>
</template>

<script>
import Work from "../components/work_with_us";
import Talk from "../components/ready_talk";
import HERO from "../";
import Home from "../src/views/Home";

export default {
  name: "App",

  components: {
    Work,
    HERO,
    Talk,
    Home,
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
