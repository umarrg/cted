<template>
  <v-app class="custom__bg">
    <v-container>
      <div class="headline  d-flex justify-center align-center mt-8">
        <v-sheet>

        </v-sheet>
       
      </div>
      <v-row justify="center" align=" center" class="mt-6">
        <v-col cols="12" md="6">
          <v-img src="../assets/contact.svg"></v-img>
          <br />
          <div>
            <h4>
              CENTRE FOR TRADE AND ENTERPRISE DEVELOPMENT (CTED).
            </h4>
          </div>
          <v-divider class="mt-2 mb-4"></v-divider>
          <div class="d-flex justify-start align-start">
            <div class="text-icon">
              <v-icon color="">mdi-google-maps</v-icon>
              Second Floor Abuja Enterprise Development Agency Complex, Plot 74
              Zone B15, Jahi Abuja.
            </div>
          </div>
          <div class="d-flex justify-start align-start">
            <a class="custom__col">
              <v-icon color="">mdi-phone</v-icon>
              +2457016505825
            </a>
          </div>
          <div class="d-flex justify-start align-start">
            <a class="custom__col">
              <v-icon color="">mdi-email</v-icon>
              umarabuabakar@gmail.com
            </a>
          </div>
        </v-col>
        <v-col cols="12" md="6">
          <v-card class="elevation-0 transparent">
            <v-flex xs12 v-if="!subscribed">
              <v-text-field outlined label="Name"></v-text-field>
            </v-flex>
            <v-flex xs12 v-if="!subscribed">
              <v-text-field outlined box label="Email address"></v-text-field>
            </v-flex>
            <v-flex xs12 v-if="!subscribed">
              <v-text-field outlined box label="Phone"></v-text-field>
            </v-flex>
            <v-flex xs12 v-if="!subscribed">
              <v-textarea
                outlined
                color=""
                placeholder=""
                error-count=""
                name=""
                label="MESSAGE"
              ></v-textarea>
            </v-flex>
            <v-flex xs12 class="text-xs-center" v-if="!subscribed">
              <v-btn
                class=" mb-5"
                dark
                width="150"
                large
                @click="subscribe"
                color="#0096C7"
              >
                Send</v-btn
              >
            </v-flex>
            <v-flex xs12 class="text-center" v-if="subscribed">
              <v-img src="../assets/msent.svg" width="900"></v-img>
              
              <v-alert type="success" border="left" elevation="" class="mt-5" prominent >
                Message sent succefully
              
              </v-alert>
              
            </v-flex>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>
<script>
export default {
  data: function() {
    return {
      subscribed: false,
    };
  },
  methods: {
    subscribe: function() {
      this.subscribed = !this.subscribed;
    },
  },
};
</script>

<style scoped>
.custom__col {
  color: #0096c7;
}
.custom__bg {
  background: white;
}
</style>
