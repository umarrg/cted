<template>
  <v-app color="white">
    <v-container>
      <v-row justify="center" align="center">
        <v-col cols="12" md="6">
          <v-img src="../assets/work.svg"></v-img>
        </v-col>
        <v-col cols="12" md="6">
          <v-col cols="12" md="12">
            <v-hover>
              <template v-slot:default="{ hover }">
                <v-card :elevation="hover ? 5 : 3" class="mx-auto " >
                  <v-card-text>
                    <v-vard-title>
                      Build your startup
                    </v-vard-title>
                    <v-card-text>
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                      Perferendis voluptates, et omnis tempore blanditiis ipsam!
                      Velit labore accusamus perspiciatis blanditiis totam error
                      fugiat, tempore aliquam explicabo, in facilis officia
                      minus?
                      <br>
                      <v-btn text >
                      <a href="">Know More...</a>
                      </v-btn>
                    </v-card-text>
                  </v-card-text>
                </v-card>
              </template>
            </v-hover>
          </v-col>
          <v-col cols="12" md="12">
            <v-hover>
              <template v-slot:default="{ hover }">
                <v-card :elevation="hover ? 5 : 3" class="mx-auto pa-6">
                  <v-card-text>
                    <v-vard-title>
                      Build your startup
                    </v-vard-title>
                    <v-card-text>
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                      Perferendis voluptates, et omnis tempore blanditiis ipsam!
                      Velit labore accusamus perspiciatis blanditiis totam error
                      fugiat, tempore aliquam explicabo, in facilis officia
                      minus?
                      <br>
                      <v-btn text >
                      <a href="">Know More...</a>
                      </v-btn>
                    </v-card-text>
                  </v-card-text>
                </v-card>
              </template>
            </v-hover>
          </v-col>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>
<style scoped>
.custom__bg {
  background: white;
}
</style>
