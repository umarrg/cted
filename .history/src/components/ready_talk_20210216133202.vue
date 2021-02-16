<template>
  <v-app class="custom__bg">
    <v-container>
      <v-row justify="center" align=" center" class="mt-5">
        <div>
          <h1 class="custom__col">Ready to talk</h1>
        </div>
        <v-col cols="12" md="12">
          <div class="d-flex justify-center align-center">
            <h1>Our team is here to help.</h1>
          </div>
        </v-col>
        <v-col cols="12" md="12">
          <div class="d-flex justify-center align-center">
            <v-btn large elevation="" color="" class="mx-4">Learn More</v-btn>
            <v-btn large elevation="" color="#0096c7" class="white--text"
              >Contact Sale</v-btn
            >
          </div>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>
<style scoped>
.custom__col {
  color: #0096c7;
}
.custom__bg{
    background: #f2f5f8;
}
</style>
