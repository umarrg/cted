<template>
  <v-app>
    <v-app-bar app>
      <v-spacer></v-spacer>

      <v-btn ou>
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
