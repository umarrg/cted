<template>
  <v-app>
    <v-container>
    <v-row justify-center align-center>
      
         <v-col cols="12" md="6">
              <div>
                <h1>READY TO TALK?</h1>
              </div>
              <div>
                <h1 class="custom__color">Our tearm is here to Talk.</h1>
              </div>
            </v-col>
            <v-col cols="12" md="6">
              <v-btn large color="#0096C7" class="white--text mx-7"
                >CONTACT US</v-btn
              >
              <v-btn large>LEARN MORE</v-btn>
            </v-col>
     
     
      
    
    </v-row>
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
.custom__color{
  color: #0096C7;
}
</style>
