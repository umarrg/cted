<template>
  <v-app>
    <v-app-bar app>
      <v-app-bar-title>CTED</v-app-bar-title>

      <v-spacer></v-spacer>

      <v-btn>
        <span class="mr-2">Latest Release</span>
        <v-icon>mdi-open-in-new</v-icon>
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
