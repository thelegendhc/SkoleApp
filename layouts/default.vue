<template>
  <v-app dark>
    <v-app-bar class="d-flex justify-center" app>
      <v-img>
        <img src="~/assets/logitrans-logo.png" alt="Your image" />
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
          cols="12"
          sm="4"
          class="d-flex justify-center"
        >
          <v-btn
          icon
          height="100px"
          width="100px"
          to="/lager"
          >
            <v-icon size="100px">mdi-library-shelves</v-icon>
          </v-btn>
        </v-col>
        <v-col
          cols="12"
          sm="4"
          class="d-flex justify-center"
        >
          <v-btn
          icon
          height="100px"
          width="100px"
          to="/opgaver"
          >
            <v-icon size="100px">mdi-checkbox-multiple-marked-outline</v-icon>
          </v-btn>
        </v-col>
        <v-col
          cols="12"
          sm="4"
          class="d-flex justify-center"
        >
          <v-btn
          icon
          height="100px"
          width="100px"
          to="/guides"
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
