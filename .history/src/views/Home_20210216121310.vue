<template>
  <v-app class="custom__bg">
    <v-container>
      <v-row>
        <v-col cols="12" md="6" class="mt-8">
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
          <div>
            <v-sheet elevation="2">
              <v-card-text class="pa-1">
                <div class="d-flex justify-spaceBetween">
                  <v-text-field prepend-icon="search"></v-text-field>
                  <v-btn
                    large
                    height="70"
                    color="#40C075"
                    class="white--text mx-2"
                    >Search</v-btn
                  >
                </div>
              </v-card-text>
            </v-sheet>
          </div>
        </v-col>
        <v-col cols="12" md="6" class="mt-8 mb-6">
          <div>
            <v-img
              src="."
              height="300"
            ></v-img>
          </div>
        </v-col>

        <v-col cols="5" class="px-2 py-0">
          <v-divider class="mt-4"></v-divider>
        </v-col>
        <v-col cols="1" class="px-2 py-0">
          <p class="ml-2">Partners</p>
        </v-col>
        <v-col cols="6" class="px-2 py-0">
          <v-divider class="mt-4"></v-divider>
        </v-col>
        <v-row class="mt-5">
          <v-col cols="2">
            <h3>Facebook</h3>
          </v-col>
          <v-col cols="2">
            <h3>Facebook</h3>
          </v-col>
          <v-col cols="2">
            <h3>Facebook</h3>
          </v-col>
          <v-col cols="2">
            <h3>Facebook</h3>
          </v-col>
          <v-col cols="2">
            <h3>Facebook</h3>
          </v-col>
          <v-col cols="2">
            <h3>Facebook</h3>
          </v-col>
        </v-row>
      </v-row>
    </v-container>
    <Work />
    <Team />
    <Talk/>
    <Footer/>
    
  </v-app>
</template>

<script>
// @ is an alias to /src
import Work from "../components/work_with_us";
import Team from "../components/meet_team";
import Talk from "../components/ready_talk";
import Footer from "../components/footer";


export default {
  name: "Home",
  components: {
    Work,
    Team,
    Talk,
    Footer
   
  },
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
