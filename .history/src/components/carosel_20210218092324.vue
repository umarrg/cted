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
          <v-col cols="3">
            <v-card class="white">
              <v-card-text>
                <h1>title</h1>
                <p>content</p>
              </v-card-text>
            </v-card>
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
