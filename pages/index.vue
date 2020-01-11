<template>
  <v-layout
    column
    justify-center
  >
    <v-container>
      <v-row class="mt-4">
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
      <v-row class="mt-4">
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
      <v-row class="mt-4">
        <v-col cols="12">
          <v-row>
            <v-col>
              <v-row align="center" justify="center">
                <h1>Our product values:</h1>
              </v-row>
            </v-col>
          </v-row>
          <v-row>
            <v-col>
              <p class="text-xs-right"><v-icon>mood</v-icon>Interesting tasks</p>
              <p><v-icon>mood</v-icon>Care and attentions</p>
              <p><v-icon>mood</v-icon>Flexible schedule</p>
            </v-col>
            <v-col>
              <p><v-icon>mood</v-icon>Interesting tasks</p>
              <p><v-icon>mood</v-icon>Care and attentions</p>
              <p><v-icon>mood</v-icon>Flexible schedule</p>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
      <v-row class="mt-4">
        <v-col>
          <v-card
            class="mx-auto"
            max-width="400"
            height="240"
            outlined
          >
            <v-list-item three-line>
            <v-list-item-content>
                <v-list-item-title class="headline mb-1">Course 1</v-list-item-title>
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
            max-width="400"
            height="240"
            outlined
          >
            <v-list-item three-line>
            <v-list-item-content>
                <v-list-item-title class="headline mb-1">Course 2</v-list-item-title>
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
            max-width="400"
            height="240"
            outlined
          >
            <v-list-item three-line>
            <v-list-item-content>
                <v-list-item-title class="headline mb-1">Course 3</v-list-item-title>
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
