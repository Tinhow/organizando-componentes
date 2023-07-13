<template>
  <v-app>
    <v-main>
      <MenuApp />
      <toolbar-app />
      <carousel-app />
      <footer-app />
    </v-main>
  </v-app>
</template>

<script>
import FooterApp from './components/FooterApp.vue'
import MenuApp from './components/MenuApp.vue'
import ToolbarApp from './components/ToolbarApp.vue'
import CarouselApp from './components/CarouselApp.vue'


export default {
  name: 'App',


  components: {
    FooterApp,
    MenuApp,
    ToolbarApp,
    CarouselApp,

  },

  data: () => ({
    //
  }),
}
</script>
