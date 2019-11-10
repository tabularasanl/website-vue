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

        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://www.google.com"
        target="_blank"
        text
      >
        <span class="mr-3">Word Lid</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-content>
      <Main/>
    </v-content>
  </v-app>
</template>

<script>
import Main from './components/Main'

export default {
  name: 'App',

  components: {
    Main
  },

  data: () => ({
    //
  }),
};
</script>
