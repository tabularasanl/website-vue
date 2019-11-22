<template>
  <v-app>
    <v-app-bar
      app
      color="rgba(51, 95, 112, 1)"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="./assets/logo.svg"
          transition="scale-transition"
          width="40"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://docs.google.com/forms/d/1-LjUf2RZ7Di0rZUP6DEG566dJUPrUfwCiTQtbxykBtc"
        text
      >
        <span class="mr-3">Word Lid</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-content>
      <Intro />
      <v-layout column>
        <v-flex id="main">
          <v-container id="column">
            <AboutUs/>
          </v-container>
          
        </v-flex>

      </v-layout>
      
    </v-content>
  </v-app>
</template>

<style scoped>
  #column {
    min-height: calc(95vh - 400px);
    background-color: rgba(51, 95, 112, 0.1);
  }

  #main {
    background-color: rgb(51, 95, 112, 0.1) !important;
  }
</style>

<script>
import Intro from './components/Intro'
import AboutUs from './components/AboutUs'

export default {
  name: 'App',

  components: {
    Intro,
    AboutUs
  },

  // data: () => ({
  //   //
  // }),
};
</script>
