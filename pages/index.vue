<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <v-card>
        <v-row justify="space-around">
          <v-col>
            <v-icon>mdi-domain</v-icon>
            <v-icon>home</v-icon>
            <v-icon>fas fa-lock</v-icon>
            <font-awesome-icon :icon="['fas', 'lock']"></font-awesome-icon>
          </v-col>
        </v-row>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import { faClock, faCity } from '@fortawesome/free-solid-svg-icons'
export default {
  data: () => ({
    icons: {
      clock: faClock,
      city: faCity
    }
  })
}
</script>
