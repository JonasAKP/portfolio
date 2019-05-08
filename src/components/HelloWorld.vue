<template>
  <v-container>
    <v-layout text-xs-center wrap>
      <v-flex xs12>
        <v-parallax dark src="http://jonaskp.dk/img/para.jpg" height="600">
          <v-layout align-center column justify-center>
            <img src="../assets/logo.svg" alt="Vuetify.js" width="30%">
            <h1 class="display-2 font-weight-thin mb-3">Jonas Pedersen</h1>
            <h4 class="subheading" id="intro">My portfolio!</h4>
          </v-layout>
        </v-parallax>
      </v-flex>

      <v-flex xs12 sm12 class="my-3">
        <div class="text-xs-center">
          <h1 class="display-2 font-weight-bold mb-3">Who is Jonas?</h1>
          <p class="subheading font-weight-regular" id="web">
            I'm a relaxed and very down to earth person that likes to take things one step at a time.
            <br>I'm told that i'm a "blank" and a "blank" personality
          </p>
        </div>
      </v-flex>

      <v-flex xs12 sm12>
        <h1 class="display-2 font-weight-bold mb-3">Homepages made</h1>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="../assets/webshop-crop.png" alt height="85%" width="85%">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline text-xs-center">Webshop</div>
          </v-card-title>
          <v-card-text>
            As one of our first projects we were tasked to make a webshop while working together with the Computer Science course.
            <br>We decided on keeping things pretty simple and easy to use, with calm colors used
          </v-card-text>
        </v-card>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="../assets/organ-crop.png" alt height="85%" width="85%">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline">Organ donation</div>
          </v-card-title>
          <v-card-text id="media">
            In this project, we were tasked with collabing in class on making a website that promotes organ donation as our numbers for organ donation is quite low
            <br>For this page we tried keeping a destinct color theme, which is red.
          </v-card-text>
        </v-card>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="https://via.placeholder.com/600" alt height="85%" width="85%">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline text-xs-center">TBD</div>
          </v-card-title>
          <v-card-text>Nothing has been made yet, please come back at a later date</v-card-text>
        </v-card>
      </v-flex>

      <v-flex xs12 sm12>
        <h1 class="display-2 font-weight-bold mb-3">Media made</h1>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="../assets/mini me.png" alt height="85%" width="85%">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline text-xs-center">Mini Me</div>
          </v-card-title>
          <v-card-text>
            As one of our first projects, we were tasked with creating a small version of ourself. I commisioned an artist to make a figure i could make something out of and
            and made a illustrator file based upon that.
          </v-card-text>
        </v-card>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="../assets/poster-crop.png" alt height="85%" width="85%">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline">Promote the school</div>
          </v-card-title>
          <v-card-text>
            EASV is in decline of students! and we were tasked to go into groups and make some promo material we thought could make the student count rise again.
            Our group focused on the schools cozyness and relaxed attitude towards the students.
          </v-card-text>
        </v-card>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="../assets/gamestop-crop.png" alt height="85%" width="85%">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline text-xs-center">Gamestop promo</div>
          </v-card-title>
          <v-card-text>
            As part of our ongoing horde of projects, we were tasked with making a documentary in coopreation of an excisting company,
            and our group chose GameStop at our local mall. Sadly i can't show you this video as it's stamped highly confidential as it could lead to the firing of people
          </v-card-text>
        </v-card>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="https://via.placeholder.com/600" alt height="85%" width="85%">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline text-xs-center">TBD</div>
          </v-card-title>
          <v-card-text>
            Nothing here yet! i'll keep ya posted
          </v-card-text>
        </v-card>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="https://via.placeholder.com/600" alt height="85%" width="85%">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline text-xs-center">TBD</div>
          </v-card-title>
          <v-card-text>
            Nothing here yet! i'll keep ya posted
          </v-card-text>
        </v-card>
      </v-flex>

      <v-flex xs12 md4>
        <v-card class="elevation-0 transparent">
          <v-card-text class="text-xs-center">
            <img src="https://via.placeholder.com/600" alt height="85%" width="85%">
          </v-card-text>
          <v-card-title primary-title class="layout justify-center">
            <div class="headline text-xs-center">TBD</div>
          </v-card-title>
          <v-card-text>
            Nothing here yet! i'll keep ya posted
          </v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
</script>

<style>
</style>
