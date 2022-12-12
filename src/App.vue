<template>
  <v-app>
    <NavBar />
    <v-main>
      <router-view/>
    </v-main>
    <Footer />
  </v-app>
</template>

<script>
import NavBar from './components/NavBarr.vue';
import Footer from './components/Footer.vue';
export default {
  name: 'App',
  components: {
    NavBar,
    Footer
  },

  data: () => ({
    //
  }),
};
</script>