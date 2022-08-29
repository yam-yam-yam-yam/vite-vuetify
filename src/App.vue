<template>
  <v-app>
    <v-main>
      <v-tabs
        v-model="menus"
        background-color="primary"
      >
        <v-tab :value="0">alert</v-tab>
        <v-tab :value="1">appBar</v-tab>
      </v-tabs>
      <v-window v-model="menus">
        <v-window-item :value="0">
          <AlertComponent/>
        </v-window-item>
        <v-window-item :value="1">
          <AppbarComponent/>
        </v-window-item>
      </v-window>
    </v-main>
  </v-app>
</template>

<script>
import AlertComponent from './components/Alert.vue'
import AppbarComponent from './components/Appbar.vue'

export default {
  components: {
    AlertComponent,
    AppbarComponent
  },

  data() {
    return {
      menus:0
    }
  },
}
</script>
