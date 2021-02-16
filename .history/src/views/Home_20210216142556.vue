<template>
  <v-app class="custom__bg">
    <v-container>
      <v-row>
        <v-col cols="12" md="6" class="mt-12">
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
            <v-btn color="#59BBBB" large class="white--text">
              Get Started
            </v-btn>
          </div>
        </v-col>
        <v-col cols="12" md="6" class="mt-8 mb-6">
          <div>
            <v-img src="../assets/dr.svg"></v-img>
          </div>
        </v-col>
      </v-row>
    </v-container>
    <HERO />
    <Work />

    <Talk />

    <v-footer padless>
      <v-card flat tile class="text-center" width="100%">
        <v-card-text>
          <div>
            <v-btn v-for="text in items" :key="text" class="mx-4"  text color">
              {{text}}
           
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
// @ is an alias to /src
import Work from "../components/work_with_us";
import Talk from "../components/ready_talk";
import HERO from "../components/hero";

export default {
  name: "Home",
  components: {
    Work,
    HERO,
    Talk,
  },
  data: () => ({
    icons: ["mdi-home", "mdi-email", "mdi-calendar", "mdi-delete"],
    items: ["Product", "Pricing", "About", "Contact Us"]
  }),
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
