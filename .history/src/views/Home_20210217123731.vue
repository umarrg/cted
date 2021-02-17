<template>
  <v-app class="custom__bg">
    <v-container>
     <v-carousel
         cycle
         height=""
         hide-delimiter-background
         show-arrows-on-hover
       >
         <v-carousel-item >
           <v-sheet
             height="100%"
           >
            
           </v-sheet>
         </v-carousel-item>
       </v-carousel>
     
    </v-container>

    <Hero id="hero" />
  </v-app>
</template>

<script>
// @ is an alias to /src
import Hero from "../components/hero";

export default {
  name: "Home",
  components: {
    Hero,
  },
  data: () => ({}),
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
.text__one {
  font-weight: bold;
}
.custom__p {
  color: #2f536a;
}
</style>
