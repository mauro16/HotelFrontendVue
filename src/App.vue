<template>
  <v-app>
    <Header />
    <v-container>
      <router-view></router-view>
    </v-container>
  </v-app>
</template>

<script>
import Header from "@/components/Header.vue";
export default {
  name: "App",
  components: { Header },
  data() {
    return {
      //
    };
  }
};
</script>
