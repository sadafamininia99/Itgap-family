<template>
  <v-app>
   
    <v-main>
      <navbar/>

      <router-view/>
    </v-main>
    
  </v-app>
</template>

<script>
import Navbar from './components/Navbar.vue';

export default {
  components: { Navbar },
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
