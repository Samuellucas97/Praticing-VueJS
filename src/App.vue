<template>
  <v-app class="indigo">
    <span class="bg"></span>
    <v-content>
      <About/>
      <Footer/>
    </v-content>
  </v-app>
</template>

<script>
import About from './components/About';
import Footer from './components/Footer';

export default {
  name: 'App',

  components: {
    About,
    Footer
  },

  data: () => ({
    //
  }),
};
</script>

<style>
.bg {
  width: 100%;
  height: 100%;
  position: absolute;
  background: url( './assets/background.png') no-repeat center center;
  transform: scale(1);
}
a {
  
}
img {
  margin: 200px 0 0;
}
</style>