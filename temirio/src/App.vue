<template>
  <v-app>
    <v-app-bar app color="primary" dark></v-app-bar>

    <v-content>
      <Card />
    </v-content>
  </v-app>
</template>

<script>
import Card from "./components/Card";

export default {
  name: "App",

  components: {
    Card
  },

  data: () => ({
    //
  })
};
</script>
