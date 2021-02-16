<template>
  <v-app>
    <Navbar v-if="$route.meta.showHeader == true" />
    <v-main> </v-main>
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
