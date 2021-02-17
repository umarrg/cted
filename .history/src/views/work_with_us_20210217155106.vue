<template>
  <v-app color="white">
    <div>
      <v-sheet color="#3F3D56" width="100%" height="70">
        <h2
          class="headline  d-flex justify-center align-center  white--text pt-5"
        >
          About Us
        </h2>
      </v-sheet>
    </div>
    <v-container>
      <v-row justify="center" align="center">
        <div class="mt-5">
          <h3 class="custom__typho">INTRODUCTION</h3>
        </div>
        <v-col cols="12 ">
          <div class="d-flex justify-center align-center ">
            <h1>
              Get your startup ready for business
            </h1>
          </div>
        </v-col>
        <v-col cols="12 ">
          <div class="d-flex justify-center align-center ">
            <p>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aliquid
              porro eveniet unde at. Molestiae repellat eius repudiandae illo
              voluptatem hic, quisquam placeat? Autem labore dolorum eaque.
              Blanditiis non eius libero Lorem ipsum, dolor sit amet consectetur
              adipisicing elit. Voluptatibus odio eius dolore ut atque dolorem
              iure quis repellendus doloremque, repudiandae quam expedita sed
              voluptatem eum nisi unde quo vitae blanditiis.
            </p>
          </div>
        </v-col>

        <v-col cols="12" md="6">
          <v-hover>
            <template v-slot:default="{ hover }">
              <v-card :elevation="hover ? 15 : 4" class="mx-auto pa-6">
                <v-card-text class="pa-0">
                  <v-list>
                    <v-list-item>
                      <v-list-item-icon>
                        <v-avatar color="#F2F5F8" rounded>
                          <v-icon color=""> mdi-account</v-icon>
                        </v-avatar>
                      </v-list-item-icon>

                      <div class="mt-6">
                        <h4>Account varification</h4>
                        <p>
                          Lorem ipsum dolor sit, amet consectetur adipisicing
                          elit. Mollitia, sint fuga dolorem praesentium amet
                          impedit delectus aliquid. Consequatur sint accusantium
                          laudantium harum natus quae iusto beatae, debitis
                          doloribus quam perspiciatis?
                        </p>
                      </div>
                    </v-list-item>
                  </v-list>
                </v-card-text>
              </v-card>
            </template>
          </v-hover>
        </v-col>
       
       
      </v-row>
    </v-container>
  </v-app>
</template>

<style scoped>
.custom__typho {
  color: #0096c7;
}
</style>
