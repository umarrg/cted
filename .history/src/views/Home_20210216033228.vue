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
            <div class="d-flex justify-spaceBetween">
            <v-text-field  prepend-icon="mdi-search"
            ></v-text-field>
            <v-btn large height="60">Search</v-btn>
            </div>
               
            </v-sheet>
          </div>
        </v-col>
        <v-col cols="12" md="6"> </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
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
