<template>
  <v-app>
    <v-main>
      <AlertComponent/>
    </v-main>
  </v-app>
</template>

<script>
import AlertComponent from './components/Alert.vue'

export default {
  components: {
    AlertComponent,
  },

  data() {
    return {
      
    }
  },
}
</script>
