<template>
  <v-app class="custom__bg">
    <v-sheet class="custom__sheet" width="100%">
      <h2
        class="headline  d-flex justify-center align-center  white--text pt-10 pb-10"
      >
        How it work
      </h2>
    </v-sheet>
    <v-container class="mt-">
      <div class="d-flex align-center justify-center">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur
          culpa temporibus excepturi quia adipisci aliquid ev
        </p>
      </div>
      <div class="d-flex align-center justify-center">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur
          culpa temporibus excepturi quia adipisci aliquid ev
        </p>
      </div>
    </v-container>

    <v-container>
      <v-row class="mt-8" justify="center" align="center">
        <v-col cols="12" md="4">
          <v-img src="../assets/cert.svg" height="200" width="200"></v-img>
        </v-col>
        <v-col cols="12" md="4">
          <v-img src="../assets/collect.svg" height="200" width="200"></v-img>
        </v-col>
        <v-col cols="12" md="4" l>
          <v-img src="../assets/mydocs.svg" height="200" width="200"></v-img>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>
<style scoped>
.custom__bg {
  background: #f2f5f8;
  height: 40em;
}
.custom__sheet {
  background: #b3d1ca;
}
</style>
