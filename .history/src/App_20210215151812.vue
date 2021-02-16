<template>
  <v-app>
    <v-app-bar app color="white">

      <v-toolbar-title colo><h2>CTED</h2></v-toolbar-title>
      <v-spacer></v-spacer>

      <v-btn rounded class="white--text" color="#0277bd">
        <span class="mr-2">ABOUT</span>
      </v-btn>
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
  background: #0277bd;
}
</style>
