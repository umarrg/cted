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
              <v-list>
                <v-list-item>
                  <v-list-item-icon>
                    <v-avatar>
                      <v-icon color="mdi-email"></v-icon>
                    </v-avatar>
                  </v-list-item-icon>
                  <v-list-item-title>
                      We are great
                  </v-list-item-title>
                </v-list-item>
              </v-list>
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
