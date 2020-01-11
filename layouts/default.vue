<template>
  <v-app>
    <v-app-bar
      :clipped-left="clipped"
      color="yellow accent-3"
      fixed
      app
    >
      <v-img
        class="mx-2"
        src="/v.png"
        max-height="40"
        max-width="100"
        contain
      />
      <v-toolbar-title v-text="title" />
      <v-spacer />
      <v-btn rounded color="pink accent-2" class="mr-3" darkd depressed>Courses</v-btn>
      <v-btn rounded color="pink accent-2" class="mr-3" dark>About</v-btn>
      <v-btn rounded color="pink accent-2" class="mr-3" dark>Contact</v-btn>
      <v-btn rounded color="pink accent-2" dark>Sign In</v-btn>
    </v-app-bar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <v-footer
      :fixed="fixed"
      app
    >
      <span>&copy; 2019</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  }
}
</script>
