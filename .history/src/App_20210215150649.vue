<template>
  <v-app>
    <v-app-bar app color="white">
      <v-spacer></v-spacer>

      <v-btn  rounded>
        <span class="mr-2" class="">ABOUT</span>
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
