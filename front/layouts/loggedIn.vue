<template>
  <v-app>
    <logged-in-app-bar />
    <v-main>
      <nuxt />
    </v-main>
  </v-app>
</template>

<script>
import loggedInAppBar from '~/components/loggedIn/header/loggedInAppBar'

export default {
  loggedInAppBar
}
</script>
