<template>
  <v-container class="mt-5">
    <v-carousel
      :dark="$vuetify.theme.dark"
      :light="!$vuetify.theme.dark"
      cycle
      height="200"
      hide-delimiters
      background-color="primary"
      show-arrows-on-hover
    >
      <v-carousel-item>
       <v-row>
           <v-card>
               <v-card-text>
                   <div class="d-flex justify-center align-center">
                       

                   </div>
               </v-card-text>
           </v-card>
       </v-row>
      </v-carousel-item>
    </v-carousel>
  </v-container>
</template>
<script>
export default {
  data() {
    return {};
  },
};
</script>
