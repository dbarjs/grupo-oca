<template>
  <v-app dark>
    <v-app-bar app color="transparent" elevation="0">
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <logo></logo>
    </v-app-bar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <v-footer app>
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
