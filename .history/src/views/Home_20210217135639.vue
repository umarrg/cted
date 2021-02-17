<template>
  <v-app>
    <v-carousel cycle color="" height="100%" hide-delimiter-background>
      <v-carousel-item>
        <v-sheet color="#f2f5f8" height="100%">
          <v-container>
            <v-row>
              <v-col cols="12" md="6" class="mt-12">
                <div>
                  <h1 class="display-2 text__one">
                    CENTRE FOR TRADE AND ENTERPRISE DEVELOPMENT
                    <span class="custom__color">(CTED)</span>
                  </h1>
                </div>

                <div class="mt-12">
                  <p class="custom__p mt-8">
                    TECHNICAL SUPPORT TO CAPACITY BUILDING FOR EXPORT PROMOTION
                    FOR MSMEs AND YOUTH OWNED BUSINESSES IN NIGERIA TOWARDS
                    INCREASING THE COUNTRY’S BENEFIT FROM AFCFTA & OTHER ONGOING
                    BILATERAL AGREEMENTS.
                  </p>
                </div>

                <!-- <div class="mt-8">
                  <v-btn color="#59BBBB" large class="white--text" href="#hero">
                    Get Started
                  </v-btn>
                </div> -->
              </v-col>
              <v-col cols="12" md="6" lg="6" class="mt-8 mb-6">
                <div>
                  <v-img src="../assets/ca1.svg"></v-img>
                </div>
              </v-col>
            </v-row>
          </v-container>
        </v-sheet>
      </v-carousel-item>
      <v-carousel-item>
        <v-sheet color="#f2f5f8" height="100%">
          <v-container>
            <v-row>
              <v-col cols="12" md="6" lg="6" class="mt-12">
                <div>
                  <h1 class="display-2 text__one">
                    CENTRE FOR TRADE AND ENTERPRISE DEVELOPMENT
                    <span class="custom__color">(CTED)</span>
                  </h1>
                </div>

                <div class="mt-12">
                  <p class="custom__p mt-8">
                    TECHNICAL SUPPORT TO CAPACITY BUILDING FOR EXPORT PROMOTION
                    FOR MSMEs AND YOUTH OWNED BUSINESSES IN NIGERIA TOWARDS
                    INCREASING THE COUNTRY’S BENEFIT FROM AFCFTA & OTHER ONGOING
                    BILATERAL AGREEMENTS.
                  </p>
                </div>

                <!-- <div class="mt-8">
                  <v-btn color="#59BBBB" large class="white--text" href="#hero">
                    Get Started
                  </v-btn>
                </div> -->
              </v-col>
              <v-col cols="12" md="6" lg="6" class="mt-8 mb-6">
                <div>
                  <v-img src="../assets/ca3.svg"></v-img>
                </div>
              </v-col>
            </v-row>
          </v-container>
        </v-sheet>
      </v-carousel-item>
      <v-carousel-item>
        <v-sheet color="#f2f5f8" height="100%">
          <v-container>
            <v-row>
              <v-col cols="12" md="6" lg="6" class="mt-12">
                <div>
                  <h1 class="text__one display-2">
                    CENTRE FOR TRADE AND ENTERPRISE DEVELOPMENT
                    <span class="custom__color">(CTED)</span>
                  </h1>
                </div>

                <div class="mt-12">
                  <p class="custom__p">
                    TECHNICAL SUPPORT TO CAPACITY BUILDING FOR EXPORT PROMOTION
                    FOR MSMEs AND YOUTH OWNED BUSINESSES IN NIGERIA TOWARDS
                    INCREASING THE COUNTRY’S BENEFIT FROM AFCFTA & OTHER ONGOING
                    BILATERAL AGREEMENTS.
                  </p>
                </div>
                <!-- 
                <div class="mt-8">
                  <v-btn color="#59BBBB" large class="white--text" href="#hero">
                    Get Started
                  </v-btn>
                </div> -->
              </v-col>
              <v-col cols="12" md="6" lg="6" class="mt-8 mb-6">
                <div>
                  <v-img src="../assets/ca4.svg"></v-img>
                </div>
              </v-col>
            </v-row>
          </v-container>
        </v-sheet>
      </v-carousel-item>
    </v-carousel>

    <!-- <Hero id="hero" /> -->
  </v-app>
</template>

<script>
// @ is an alias to /src
// import Hero from "../components/hero";

export default {
  name: "Home",
  components: {},
  data: () => ({}),
};
</script>
<style scoped>
.custom__divider {
  height: 16rem;
  color: #0277bd;
}
.custom__bg {
  background: #f2f5f8;
}
.white__bg {
  background: white;
}
.custom__color {
  color: #0096c7;
}
.text__one {
  font-weight: bold;
  color: black;
}
.custom__p {
  color: #2f536a;
}
</style>
