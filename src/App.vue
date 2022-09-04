<template>
  <v-app>
    <v-main>
      <v-tabs
        v-model="menus"
        background-color="primary"
      >
        <v-tab :value="0">alert</v-tab>
        <v-tab :value="1">appBar</v-tab>
        <v-tab :value="2" disabled>avatar</v-tab>
        <v-tab :value="3">badge</v-tab>
        <v-tab :value="4">btn</v-tab>
        <v-tab :value="5">card</v-tab>
      </v-tabs>
      <v-window v-model="menus">
        <v-window-item :value="0">
          <AlertComponent/>
        </v-window-item>
        <v-window-item :value="1">
          <AppbarComponent/>
        </v-window-item>
        <v-window-item :value="2">
          <AvatarComponent/>
        </v-window-item>
        <v-window-item :value="3">
          <BadgeComponent/>
        </v-window-item>
        <v-window-item :value="4">
          <ButtonComponent/>
        </v-window-item>
        <v-window-item :value="5">
          <CardComponent/>
        </v-window-item>
      </v-window>
    </v-main>
  </v-app>
</template>

<script>
import AlertComponent from './components/Alert.vue'
import AppbarComponent from './components/Appbar.vue'
import AvatarComponent from './components/Avatar.vue'
import BadgeComponent from './components/Badge.vue'
import ButtonComponent from './components/Button.vue'
import CardComponent from './components/Card.vue'

export default {
  components: {
    AlertComponent,
    AppbarComponent,
    AvatarComponent,
    BadgeComponent,
    ButtonComponent,
    CardComponent
  },

  data() {
    return {
      menus:0
    }
  },
}
</script>
