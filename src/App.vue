<template>
  <v-app>
    <Load />
    <Header />
    <Footer />
    <v-container>
      <router-view></router-view>
    </v-container>
  </v-app>
</template>

<script>
import Load from "@/components/Load.vue";
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "App",
  components: { Load, Header, Footer },
  data() {
    return {
      //
    };
  }
};
</script>
