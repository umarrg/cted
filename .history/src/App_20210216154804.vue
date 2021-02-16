<template>
  <v-app>
    <v-app-bar app color="white" elevation="3">
      <v-toolbar-title><h2 class="custom__colour">CTED</h2></v-toolbar-title>
      <v-spacer></v-spacer>

      <v-toolbar-items>
        <v-btn flat class="mx-2" href="../components/ready">About</v-btn>

        <v-btn flat class="white--text" color="#0096C7">Contact Us</v-btn>
      </v-toolbar-items>
    </v-app-bar>

    <v-main>
      <router-view></router-view>
    </v-main>

  </v-app>
</template>

<script>
export default {
  name: "App",

  components: {},

  data: () => ({
    //
  }),
};
</script>

<style scoped>
.custom__colour {
  color: #0096c7;
}
</style>
