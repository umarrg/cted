<template>
  <v-app class="custom__bg">
    <v-container>
      <v-row>
        <v-col cols="12" md="6"  lg="6" class="mt-12">
          <div>
            <h1 class="display-2 text__one">
              A better way to start your task
              <span class="custom__color">cted project</span>
            </h1>
          </div>

          <div class="mt-6">
            <p class="custom__p">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Non
              laborum labore nemo explicabo quo neque facere libero at ut fuga,
              autem velit vel dignissimos error consectetur dicta sequi. Unde,
              ab?
            </p>
          </div>

          <div class="mt-8">
            <v-btn color="#59BBBB" large class="white--text" href="#hero">
              Get Started
            </v-btn>
          </div>
        </v-col>
        <v-col cols="12" md="6"  class="mt-8 mb-6">
          <div>
            <v-img src="../assets/dr.svg"></v-img>
          </div>
        </v-col>
      </v-row>
    </v-container>

    <Hero id="hero" />
  </v-app>
</template>

<script>
// @ is an alias to /src
import Hero from "../components/hero";

export default {
  name: "Home",
  components: {
    Hero,
  },
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
}
.custom__p {
  color: #2f536a;
}
</style>
