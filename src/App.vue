<template>
  <v-app>
    <Navbar/>
    <v-main>
      <Home/>
      <Gallery/>
    </v-main>
  </v-app>
</template>
<script>
// import Slider from './components/slider.vue'

import Navbar from "@/components/Navbar.vue";
import Home from "@/components/Home.vue";
import Gallery from "@/components/Gallery.vue";


export default {
  name: 'app',
  components: {
    Gallery,
    Home,
    Navbar

  }
}
</script>
