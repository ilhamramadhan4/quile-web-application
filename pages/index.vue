<template>
  <v-layout
    column
    justify-center
  >
    <v-container>
      <v-row>
        <v-col>
          <v-layout d-flex align-start>
            <h1>Our tagline goes here!!</h1>
          </v-layout>
        </v-col>
        <v-col>
          <v-layout align-end justify-end>
            <img
              src="/v.png"
              alt="Vuetify.js"
              class="mb-5"
            />
          </v-layout>
        </v-col>
      </v-row>
      <v-row>
        <v-col>
          <v-card
            class="mx-auto"
            max-width="600"
            outlined
          >
            <v-list-item three-line>
            <v-list-item-content>
                <v-list-item-title class="headline mb-1">Innovative courses with lots variety of subject</v-list-item-title>
                <v-card-text>
                  "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
                  Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
                  Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
                </v-card-text>
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
        <v-col>
          <v-card
            class="mx-auto"
            max-width="600"
            outlined
          >
            <v-list-item three-line>
            <v-list-item-content>
                <v-list-item-title class="headline mb-1">Innovative courses with lots variety of subject</v-list-item-title>
                <v-card-text>
                  "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
                  Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
                  Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
                </v-card-text>
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
      </v-row>
      <v-row>
        <h1>Our tagline goes here!!</h1>
      </v-row>
      <v-row>
        <h1>Our tagline goes here!!</h1>
      </v-row>
    </v-container>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
