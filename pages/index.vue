<template>
    <v-container>
        <v-row>
          <v-col sm="12" align="center" justify="center" cols="12">
            <v-avatar size="80">
              <img
                src="~/assets/nuxt-icon.png"
                alt="Nuxt Icon"
              >
            </v-avatar>
            <h1 class="title">
              NuxtJS and Vuetify
            </h1>
            <p class="caption">Starterkit</p>
          </v-col>
        </v-row>
    </v-container>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>
