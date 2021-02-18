<template>
  <v-container>
    <v-carousel
      cycle
      height="100"
      hide-delimiter-background
      show-arrows-on-hover
    >
      <v-carousel-item>
        <v-row>
          <v-col cols="3" md="3">
              vca
            <div class="d-flex justify-center align-center">
              <v-avatar>
                <v-icon color="">mdi-account</v-icon>
              </v-avatar>

              <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quo
                aspernat
              </p>
            </div>
          </v-col>
        </v-row>
      </v-carousel-item>
    </v-carousel>
  </v-container>
</template>
<script>
export default {
  data() {
    return {};
  },
};
</script>
