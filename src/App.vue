<template>
<div class="app">
  <v-app light>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <v-img
          :src="require('@/assets/logo.svg')"
          class="mr-5"
          contain
          flex
          height="48"
          width="48"
          max-width="48"
          @click="$vuetify.goTo(0)"
        />
      </v-toolbar-title>
      <v-spacer></v-spacer>

      <v-btn flat href="#intro" class="hidden-sm-and-down">
        <span class="mr-2">Intro</span>
      </v-btn>

      <v-btn flat href="#web" class="hidden-sm-and-down">
        <span class="mr-2">Webpages</span>
      </v-btn>

      <v-btn flat href="#media" class="hidden-sm-and-down">
        <span class="mr-2">Multimedia</span>
      </v-btn>

      <v-menu offset-y>
        <template v-slot:activator="{ on }">
          <v-btn class="hidden-md-and-up" flat v-on="on">Menu</v-btn>
        </template>
        <v-list>
          <v-list-tile href="#intro">Intro</v-list-tile>
          <v-list-tile href="#web">Webpages</v-list-tile>
          <v-list-tile href="#media">Multimedia</v-list-tile>
        </v-list>
      </v-menu>
    </v-toolbar>

    <v-content>
      <HelloWorld/>
    </v-content>

    <v-footer class="teal">
      <v-layout row wrap align-center>
        <v-flex xs12>
          <div class="white--text ml-3">
            Made
            with
            <a
              class="white--text"
              href="https://vuetifyjs.com"
              target="_blank"
            >Vuetify</a>
            by Jonas Pedersen
          </div>
        </v-flex>
      </v-layout>
    </v-footer>
  </v-app>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  },
  data() {
    return {
      //
    };
  }
};
</script>
