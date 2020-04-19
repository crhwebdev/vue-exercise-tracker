<template>
  <v-container>
    <div class="home">
      <img alt="Vue logo" src="../assets/logo.png" @click="clickMessage" />
      <v-btn small to="/vuetify">Vuetify</v-btn>
      <v-btn small to="/about">About</v-btn>
    </div>
  </v-container>
</template>

<script>
export default {
  name: "Home",
  methods: {
    clickMessage() {
      console.log("Clicked me!");
    },
  },
};
</script>
