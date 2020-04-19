<template>
  <v-container>
    <div class="home">
      <img alt="Vue logo" src="../assets/logo.png" @click="clickMessage" />
      <v-btn small to="/vuetify">Vuetify</v-btn>
      <v-btn small to="/about">About</v-btn>
      <div class="greeting">
        <p>Hello World!</p>
      </div>
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

<style scoped lang="scss">
.greeting {
  p {
    color: red;
  }
}
</style>
