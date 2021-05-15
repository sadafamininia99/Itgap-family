<template>
  <v-main>
    <div class="d-flex justify-center align-center flex-column">
       <img src="../assets/itgap.png" height="256" width="256" class="rounded-pill" />
       <h1 class="mt-12" >
         ITGAP Family
       </h1>
    </div>
    <btns class="d-flex justify-center align-center mt-16 flex-wrap" />
   
  
  </v-main>
</template>

<script>
import Btns from '../components/Btns.vue'


  export default {
    name: 'Home',

    components: {
        Btns
     
    },
  }
</script>

<style lang="scss" scoped>
img{
  filter: drop-shadow(2px 4px 8px #585858);
}


</style>