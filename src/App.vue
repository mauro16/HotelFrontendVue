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
export default {
  data() {
    return {
      //
    };
  }
};
</script>
