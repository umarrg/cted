<template>
  <v-app>
    <v-app-bar app color="white" elevation="3">
      <v-toolbar-title
        >     <v-btn text to="/">
         <h2 class="custom__colour">CTED</h2>
         </v-btn>
         
         </v-toolbar-title
      >
      <v-spacer></v-spacer>

      <v-toolbar-items>
        <v-btn flat class="mx-2" href="#about">About</v-btn>

        <v-btn flat class="white--text" color="#0096C7" href="#contact"
          >Contact Us</v-btn
        >
      </v-toolbar-items>
    </v-app-bar>
    <v-main>
      <Home id="home" />
      <HERO />
      <Work id="about" />

      <Talk id="contact" />
    </v-main>

    <v-footer padless>
      <v-card flat tile class="text-center" width="100%">
        <v-card-text>
          <div class="mb-7">
            <v-btn
              v-for="text in items"
              :key="text"
              class="mx-4"
              text
              color="#0096c7"
            >
              {{ text }}
            </v-btn>
          </div>
          <v-btn v-for="icon in icons" :key="icon" class="mx-4" icon>
            <v-icon size="24px">
              {{ icon }}
            </v-icon>
          </v-btn>
        </v-card-text>
      </v-card>
    </v-footer>
  </v-app>
</template>

<script>
import Work from "../src/components/work_with_us";
import Talk from "../src/components/ready_talk";
import HERO from "../src/components/hero";
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
    icons: ["mdi-facebook", "mdi-twitter", "mdi-google", "mdi-linkedin"],
    items: ["Product", "Pricing", "About", "Contact Us"],
    //
  }),
};
</script>

<style scoped>
.custom__colour {
  color: #0096c7;
}
</style>
