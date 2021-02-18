<template>
  <v-app>
    <v-sheet color="#f2f5f8">
      <v-container>
        <v-row>
          <v-col cols="12" md="6" class="mt-12">
            <div class="mt-8">
              <h1 class="display-2 text__one">
                CENTRE FOR TRADE AND ENTERPRISE DEVELOPMENT
                <span class="custom__color">(CTED)</span>
              </h1>
            </div>

            <div class="mt-12">
              <p class="custom__p mt-8">
                TECHNICAL SUPPORT TO CAPACITY BUILDING FOR EXPORT PROMOTION FOR
                MSMEs AND YOUTH OWNED BUSINESSES IN NIGERIA TOWARDS INCREASING
                THE COUNTRY’S BENEFIT FROM AFCFTA & OTHER ONGOING BILATERAL
                AGREEMENTS.
              </p>
            </div>
          </v-col>
          <v-col cols="12" md="6" lg="6" class="mt-5 mb-5">
            <div>
              <v-img src="../assets/ca1.svg"></v-img>
            </div>
          </v-col>
        </v-row>

        <div class="mt-0 d-flex justify-center align-center">
          <v-btn
            color="#59BBBB"
            fab
            elevation="1"
            class="white--text"
            href="#hero"
          >
            <v-icon>mdi-chevron-double-down</v-icon>
          </v-btn>
        </div>
      </v-container>
    </v-sheet>
    <Hero id="hero" />
    <Section />
  </v-app>
</template>

<script>
// @ is an alias to /src
import Hero from "../components/hero";
import Carosel from '../components/carosel'
import Section from '../components/section.vue';

export default {
  name: "Home",
  components: {
    Hero,
    Section
    Caro
    
  },
  data: () => ({}),
};
</script>
<style scoped>
.custom__divider {
  height: 16rem;
  color: #845b79;
}
.custom__bg {
  background: #f2f5f8;
}
.white__bg {
  background: white;
}
.custom__color {
  color: #845b79;
}
.text__one {
  font-weight: bold;
  color: black;
}
.custom__p {
  color: #2f536a;
}
</style>
