<template>
  <v-app>
    <v-app-bar app color="white">
      <v-toolbar-title><h2 class="custom__colour">CTED</h2></v-toolbar-title>
      <v-spacer></v-spacer>
      //#0096C7
     
    </v-app-bar>

    <v-main>
      <router-view></router-view>
    </v-main>
    
  </v-app>
</template>

<script>


export default {
  name: "App",

  components: {
    
    
  },

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
