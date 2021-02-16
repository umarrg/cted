<template>
  <v-app color=" #f2f5f8" class="custom__bg">
    <v-container class="">
      <v-row>
        <v-col cols="12" md="6">
          <v-img src="../assets/dr.svg"></v-img>
        </v-col>
        <v-col cols="12" md="6"> 
            <v-hover>
      <template v-slot:default="{ hover }">
        <v-card
          :elevation="hover ? 24 : 6"
          class="mx-auto pa-6"
        >
          Prop based elevation
        </v-card>
      </template>
    </v-hover>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>
<style scoped>
.custom__bg {
  background: #f2f5f8;
}
</style>
