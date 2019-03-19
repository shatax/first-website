<template>
  <v-app>
    <v-content>
      <Header/>
      <router-view />
    </v-content>
    <v-footer>
      <Footer />
    </v-footer>
  </v-app>
</template>

<script>
import Footer from "./components/Footer";
import Header from "./components/Header";
import LandingPage from "./components/LandingPage";

export default {
  name: "App",
  components: {
    Footer,
    Header,
    LandingPage
  },
  data() {
    return {
      //
    };
  }
};
</script>
