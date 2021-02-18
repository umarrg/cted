<template>
  <v-app class="custom__bg" >
   <v-sheet class="custom__sheet" width="100%" >
        <h2 class="headline  d-flex justify-center align-center  white--text pt-10 pb-10">
          LOREM
        </h2>
      </v-sheet>
      <v-row no-gutters>
      <v-col
        v-for="n in 3"
        :key="n"
        cols="12"
        sm="4"
      >
        <v-card
          class="pa-2"
          outlined
          tile
        >
          One of three columns
        </v-card>
      </v-col>
    </v-row>
        </v-app>
</template>
<style scoped>
.custom__bg {
  background: #f2f5f8;
  height: 40em;
}
.custom__sheet{
    background: #b3d1ca;
}

</style>
