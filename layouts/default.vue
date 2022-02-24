<template>
  <v-app dark>
    <v-navigation-drawer app clipped>
      test
    </v-navigation-drawer>
    <v-app-bar class="d-flex justify-center" app>
      <v-img>
        <img height="200px" src="~/assets/logitrans-logo.png" alt="Your image" />
      </v-img>
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <v-footer
      app
    >
      <v-row>
        <v-col
          cols="4"
          sm="4"
          class="d-flex justify-center"
        >
          <v-btn
          icon
          height="100px"
          width="100px"
          to="/lager"
          nuxt
          >
            <v-icon size="100px">mdi-library-shelves</v-icon>
          </v-btn>
        </v-col>
        <v-col
          cols="4"
          sm="4"
          class="d-flex justify-center"
        >
          <v-btn
          icon
          height="100px"
          width="100px"
          to="/"
          nuxt
          >
            <v-icon size="100px">mdi-checkbox-multiple-marked-outline</v-icon>
          </v-btn>
        </v-col>
        <v-col
          cols="4"
          sm="4"
          class="d-flex justify-center"
        >
          <v-btn
          icon
          height="100px"
          width="100px"
          to="/guides"
          nuxt
          >
            <v-icon size="100px">mdi-help</v-icon>
          </v-btn>
        </v-col>
      </v-row>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data () {
    return {
      
    }
  }
}
</script>
