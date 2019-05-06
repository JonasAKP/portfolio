<template>
  <v-container>
    <v-layout text-xs-center wrap>
      <v-flex xs12>
        <v-parallax dark src="http://jonaskp.dk/img/hero.jpeg" height="600">
          <v-layout align-center column justify-center>
            <img src="../assets/logo.svg" alt="Vuetify.js" height="200">
            <h1 class="display-2 font-weight-thin mb-3">Jonas Pedersen</h1>
            <h4 class="subheading">My portfolio!</h4>
          </v-layout>
        </v-parallax>
      </v-flex>

      <v-flex xs12 sm12 class="my-3">
        <div class="text-xs-center">
          <h1 class="display-2 font-weight-bold mb-3">Who is Jonas?</h1>
          <p class="subheading font-weight-regular">
            For help and collaboration with other Vuetify developers, adadadawdadadadadadadadadaddadadadadadadadadadaddadadadadadadadada
            <br>please join our online lsjgfksejbgflksbflksbflkhs bflkhwsbflsfbsefbjlshfblkrhgfblkeRHGBLKerhgblHBWGRF
          </p>
        </div>
      </v-flex>

      <v-flex xs12 sm12>
        <h1 class="display-2 font-weight-bold mb-3">Homepages made</h1>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="https://via.placeholder.com/300" alt="">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline text-xs-center">Material Design</div>
          </v-card-title>
          <v-card-text>
            Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
            Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
            Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
          </v-card-text>
        </v-card>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="https://via.placeholder.com/300" alt="">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline">Fast development</div>
          </v-card-title>
          <v-card-text>
            Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
            Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
            Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
          </v-card-text>
        </v-card>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="https://via.placeholder.com/300" alt="">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline text-xs-center">Completely Open Sourced</div>
          </v-card-title>
          <v-card-text>
            Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
            Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
            Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
          </v-card-text>
        </v-card>
      </v-flex>

<v-flex xs12 sm12>
        <h1 class="display-2 font-weight-bold mb-3">Media made</h1>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="https://via.placeholder.com/300" alt="">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline text-xs-center">Material Design</div>
          </v-card-title>
          <v-card-text>
            Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
            Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
            Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
          </v-card-text>
        </v-card>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="https://via.placeholder.com/300" alt="">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline">Fast development</div>
          </v-card-title>
          <v-card-text>
            Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
            Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
            Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
          </v-card-text>
        </v-card>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="https://via.placeholder.com/300" alt="">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline text-xs-center">Completely Open Sourced</div>
          </v-card-title>
          <v-card-text>
            Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
            Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
            Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
          </v-card-text>
        </v-card>
      </v-flex>



     
    </v-layout>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    ecosystem: [
      {
        text: "vuetify-loader",
        href: "https://github.com/vuetifyjs/vuetify-loader"
      },
      {
        text: "github",
        href: "https://github.com/vuetifyjs/vuetify"
      },
      {
        text: "awesome-vuetify",
        href: "https://github.com/vuetifyjs/awesome-vuetify"
      }
    ],
    importantLinks: [
      {
        text: "Documentation",
        href: "https://vuetifyjs.com"
      },
      {
        text: "Chat",
        href: "https://community.vuetifyjs.com"
      },
      {
        text: "Made with Vuetify",
        href: "https://madewithvuetifyjs.com"
      },
      {
        text: "Twitter",
        href: "https://twitter.com/vuetifyjs"
      },
      {
        text: "Articles",
        href: "https://medium.com/vuetify"
      }
    ],
    whatsNext: [
      {
        text: "Explore components",
        href: "https://vuetifyjs.com/components/api-explorer"
      },
      {
        text: "Select a layout",
        href: "https://vuetifyjs.com/layout/pre-defined"
      },
      {
        text: "Frequently Asked Questions",
        href: "https://vuetifyjs.com/getting-started/frequently-asked-questions"
      }
    ]
  })
};
</script>

<style>
</style>
