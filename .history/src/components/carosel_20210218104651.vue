<template>
  <v-container class="">
    <v-carousel
      :dark="$vuetify.theme.dark"
      :light="!$vuetify.theme.dark"
      cycle
      height="200"
      hide-delimiters
      background-color="primary"
      show-arrows-on-hover
    >
      <v-carousel-item>
        <v-row>
          <v-col>
            <v-card>
              <v-card-text>
                <div class="d-flex justify-center align-center">
                  <v-avatar color="ash" size="4">
                    <v-icon color="">mdi-gmail</v-icon>
                  </v-avatar>

                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Nisi exceptu
                  </p>
                </div>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col>
            <v-card>
              <v-card-text>
                <div class="d-flex justify-center align-center">
                  <v-avatar>
                    <v-icon color="">mdi-accont</v-icon>
                  </v-avatar>

                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Nisi exceptu
                  </p>
                </div>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col>
            <v-card>
              <v-card-text>
                <div class="d-flex justify-center align-center">
                  <v-avatar>
                    <v-icon color="">mdi-accont</v-icon>
                  </v-avatar>

                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Nisi exceptu
                  </p>
                </div>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col>
            <v-card>
              <v-card-text>
                <div class="d-flex justify-center align-center">
                  <v-avatar>
                    <v-icon color="">mdi-accont</v-icon>
                  </v-avatar>

                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Nisi exceptu
                  </p>
                </div>
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
