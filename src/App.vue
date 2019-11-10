<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>TheLanscapers</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
    </v-app-bar>

    <v-content>
      <HomePage />
    </v-content>
  </v-app>
</template>

<script>
import HomePage from "./components/HomePage";

export default {
  name: "App",
  components: {
    HomePage
  },
  data: () => ({
    //
  })
};
</script>
