<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <img
          class="logo_toolbar"
          src="@/assets/logo.png"
         alt=""/>
      </v-toolbar-title>
      <v-spacer></v-spacer>


        <Login></Login>


      <v-btn
        flat
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >

        <span class="mr-2">Latest Release</span>
      </v-btn>
    </v-toolbar>

    <v-content>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
import Login from './components/Login'
export default {
  name: 'App',
  components: {
    Login
  },
  data () {
    return {
      dialog:false
    }
  }
}
</script>

<style scoped>
.logo_toolbar {
  width: 50px;
  margin-top: 10px;
}
</style>

