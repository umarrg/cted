<template>
  <v-app class="custom__bg">
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
            <p>
              Nigeria boasts of the most youthful and vibrant population
              globally. Our demographic dividend and the vast youthful potential
              we have can be harnessed for our collective good and progress to
              break the cycles of poverty, conflict, hunger and inequalities
              that have plagued us in this country.
            </p>
          </div>
        </v-col>
        <v-col cols="12 ">
          <div class="d-flex justify-center align-center ">
            <p>
              According to UNCTAD, the 2030 Agenda for SDGs recognizes
              International Trade as an engine for inclusive economic growth and
              poverty reduction, and also an important means to achieve the
              SDGs. The Center for Trade and Enterprise Development ( CTED) is a
              foundation based organization that partners Federal Ministries and
              Agencies, International Organizations and private sector that work
              to implement developmental projects that improve governance,
              improves competitiveness, regional and global integration and
              foster economic efficiencies through
            </p>
          </div>
        </v-col>

        <v-col cols="12" md="6">
          <v-hover>
            <template v-slot:default="{ hover }">
              <v-card :elevation="hover ? 15 : 4" class="mx-auto pa-6">
                <v-card-text class="pa-0">
                  <v-list>
                    <v-list-item class="pa-0">
                      <v-list-item-icon>
                        <v-avatar color="#3F3D56" rounded>
                          <v-icon color="white"> mdi-trademark</v-icon>
                        </v-avatar>
                      </v-list-item-icon>

                      <div class="mt-6">
                        <h4>Trade Facilitation</h4>
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
        <v-col cols="12" md="6">
          <v-hover>
            <template v-slot:default="{ hover }">
              <v-card :elevation="hover ? 15 : 4" class="mx-auto pa-6">
                <v-card-text class="pa-0">
                  <v-list>
                    <v-list-item class="pa-0">
                      <v-list-item-icon>
                        <v-avatar color="#3F3D56" rounded>
                          <v-icon color="white"> google-my-business</v-icon>
                        </v-avatar>
                      </v-list-item-icon>

                      <div class="mt-6">
                        <h4>Business Facilitation</h4>
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
        <v-col cols="12" md="6">
          <v-hover>
            <template v-slot:default="{ hover }">
              <v-card :elevation="hover ? 15 : 4" class="mx-auto pa-6">
                <v-card-text class="pa-0">
                  <v-list>
                    <v-list-item class="pa-0">
                      <v-list-item-icon>
                        <v-avatar color="#3F3D56" rounded>
                          <v-icon color="white"> mdi-account</v-icon>
                        </v-avatar>
                      </v-list-item-icon>

                      <div class="mt-6">
                        <h4>Investment Facilitation</h4>
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
        <v-col cols="12" md="6">
          <v-hover>
            <template v-slot:default="{ hover }">
              <v-card :elevation="hover ? 15 : 4" class="mx-auto pa-6">
                <v-card-text class="pa-0">
                  <v-list>
                    <v-list-item class="pa-0">
                      <v-list-item-icon>
                        <v-avatar color="#3F3D56" rounded>
                          <v-icon color="white"> mdi-account</v-icon>
                        </v-avatar>
                      </v-list-item-icon>

                      <div class="mt-6">
                        <h4>Developmental Policy</h4>
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
.custom__bg {
  background: #f2f5f8;
}
</style>
