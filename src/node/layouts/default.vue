<template>
  <v-app>
    <Header></Header>
    <v-main>
      <Nuxt />
    </v-main>
    <Footer></Footer>
  </v-app>
</template>

<script>
import Header from "~/components/Header";
import Footer from "~/components/Footer";
export default {
  name: 'DefaultLayout',
  components: {Footer, Header},
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      // items: [
      //   {
      //     icon: 'mdi-apps',
      //     title: 'Welcome',
      //     to: '/',
      //   },
      //   {
      //     icon: 'mdi-chart-bubble',
      //     title: 'Inspire',
      //     to: '/inspire',
      //   },
      // ],
      // miniVariant: false,
      // right: true,
      // rightDrawer: false,
      // title: 'Vuetify.js',
    }
  },
}
</script>
