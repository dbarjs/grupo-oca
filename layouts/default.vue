<template>
  <v-app dark>
    <v-app-bar app color="transparent" elevation="0">
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <logo></logo>
      <v-spacer></v-spacer>
      <v-btn icon href="https://www.instagram.com/grupooca/" target="_blank">
        <v-icon>mdi-instagram</v-icon>
      </v-btn>
    </v-app-bar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <v-footer app color="transparent justify-center">
      <span class="mr-1">Cavezzo</span>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
import Logo from '~/components/Logo.vue'
export default {
  components: {
    Logo
  },
  data() {
    return {}
  }
}
</script>
