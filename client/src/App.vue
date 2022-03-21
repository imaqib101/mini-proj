<template>
  <v-app>
    <v-main> <NavBar /><FileUpload /> </v-main>
  </v-app>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import FileUpload from "./components/FileUpload.vue";

export default {
  name: "App",

  components: {
    NavBar,
    FileUpload,
  },

  data: () => ({
    //
  }),
};
</script>
