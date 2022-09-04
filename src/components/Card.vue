<template>
    <v-col cols="12">
        <v-card
            class="pa-4"
            color="#1F7087"
            theme="dark"
        >
            <template v-slot:append>
                append
            </template>
            <template v-slot:prepend>
                prepend
            </template>
            <template v-slot:title>
                title
            </template>
            <template v-slot:subtitle>
                subtitle
            </template>
            <template v-slot:text>
                text
            </template>
            <template v-slot:item>
                item
            </template>
            <template v-slot:actions>
                actions
            </template>
        </v-card>
    </v-col>
    <v-col cols="3">
        <v-card
            class="pa-4"
            color="#385F73"
            theme="dark"
        >
            <!-- <template v-slot:append>
                append
            </template>
            <template v-slot:prepend>
                prepend
            </template> -->
            <template v-slot:title>
                Unlimited music now
            </template>
            <template v-slot:subtitle class="overflow-y-auto">
                Listen to your favorite artists.
            </template>
            <template v-slot:text>
                빨리 구매하세용
            </template>
            <template v-slot:item>
                <div class="my-4 subtitle-3">
                    $ • Italian, Cafe1
                </div>
                <div class="my-4 subtitle-3">
                    $ • Italian, Cafe2
                </div>
                <div class="my-4 subtitle-3">
                    $ • Italian, Cafe3
                </div>
            </template>
            <template v-slot:actions>
                <v-btn text>Listen Now</v-btn>
            </template>
        </v-card>
    </v-col>
    <v-col cols="3">
        <v-card
            color="#1F7087"
            theme="dark"
        >
            <div class="d-flex flex-no-wrap justify-space-between">
              <div>
                <v-card-title class="text-h5">
                  Supermodel
                </v-card-title>
                <v-card-subtitle>Foster the People</v-card-subtitle>
              </div>
              <v-avatar
                class="ma-3"
                size="125"
                rounded="0"
              >
                <v-img src="https://cdn.vuetifyjs.com/images/cards/foster.jpg"></v-img>
              </v-avatar>
            </div>
        </v-card>
    </v-col>
    <v-col cols="3">
        <v-card
            color="#952175"
            theme="dark"
        >
            <div class="d-flex flex-no-wrap justify-space-between">
              <div>
                <v-card-title class="text-h5">
                  Halcyon Days
                </v-card-title>
                <v-card-subtitle>Ellie Goulding</v-card-subtitle>
                <v-card-actions>
                  <v-btn
                    class="ml-2"
                    icon="fas fa-home"
                    variant="text"
                  ></v-btn>
                </v-card-actions>
              </div>
              <v-avatar
                class="ma-3"
                size="125"
                rounded="0"
              >
                <v-img src="https://cdn.vuetifyjs.com/images/cards/halcyon.png"></v-img>
              </v-avatar>
            </div>
        </v-card>
    </v-col>
</template>

<script>
export default {

}
</script>

<style>

</style>