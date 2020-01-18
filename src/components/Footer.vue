<template>

    <v-footer
      absolute
      class="font-weight-medium"
      dark
      padless
    >
      <v-col
        class="text-center"
        cols="12"
      >
        &copy; {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
      </v-col>
    </v-footer>
 
</template>


<script>
export default {
  name: 'Footer',
}
</script>

<style>
.footer{
  margin-top: 31.7%;
}
</style>