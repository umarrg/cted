<template>
  <v-app class="custom__bg">
    <v-container>
      <v-row>
        <v-col cols="12" md="6">
         <div>
           <h1 class="display"> A better way to start your task <span class="custom__color">cted project</span></h1>
         </div>
        </v-col>
          <v-col cols="12" md="6">

        </v-col>
      </v-row>
      
       
    </v-container>
  </v-app>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
<style scoped>
.custom__divider {
  height: 16rem;
  color: #0277bd;
}
.custom__bg {
  background: #f2f5f8;
}
.white__bg {
  background: white;
}
.custom__color {
  color: #0096c7;
}
</style>
