<template>
  <v-container>
    <v-layout
      column
      align-center
      justify-center
      class="white--text layout_start"
    >
      <img
        src="@/assets/logo.png"
        alt="Vuetify.js"
        height="250"
      >
      <div class="primary--text mb-1 display-1 text-uppercase title-started text-xs-center">Le premier site de competition de tennis de table agile</div>
      <div class="primary--text font-weight-thin subheading mb-3 text-xs-center">Powered by CapsuleLab</div>
      <v-btn
        class="blue lighten-2 mt-5"
        dark
        large
        href="/pre-made-themes"
      >
        Inscription
      </v-btn><
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: 'GetStarted',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.layout_start {
  margin-top: 5%;
  font-family: "Varela Round", sans-serif !important;
}

.title-started {
  margin-top: 50px;
}
</style>
