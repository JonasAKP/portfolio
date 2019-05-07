<template>
  <v-app>
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

      <v-btn flat class="hidden-md-and-up">
        <span class="mr-2">test</span>
      </v-btn>
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
            <a class="white--text" href="https://vuetifyjs.com" target="_blank">Vuetify</a>

            by Jonas Pedersen
          </div>
        </v-flex>
      </v-layout>
    </v-footer>
  </v-app>
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
