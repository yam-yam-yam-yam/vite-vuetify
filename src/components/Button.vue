<template>
    <v-card class="pa-4 ma-4 elevation-24 bg-blue-grey-lighten-3">
        <v-btn class="mx-4">default</v-btn>
        <v-btn class="mx-4">
            <template v-slot:append>
                append
            </template>
            center
        </v-btn>
        <v-btn class="mx-4">
            <template v-slot:prepend>
                prepend
            </template>
            center
        </v-btn>
    </v-card>
    <v-card class="pa-4 ma-4 elevation-24 bg-blue-grey-lighten-3">
        <v-btn class="mx-4" flat>flat</v-btn>
        <v-btn class="mx-4" stacked>stacked</v-btn>
        <v-btn class="mx-4" :ripple="false">ripple false</v-btn>
        <v-btn class="mx-4" border>border</v-btn>
    </v-card>
    <v-card class="pa-4 ma-4 elevation-24 bg-blue-grey-lighten-3">
        <v-btn class="mx-4" density="default">default</v-btn>
        <v-btn class="mx-4" density="comfortable" elevation="0">comfortable, elevation="0"</v-btn>
        <v-btn class="mx-4" density="compact" elevation="24">compact, elevation=24</v-btn>
    </v-card>
    <v-card class="pa-4 ma-4 elevation-24 bg-blue-grey-lighten-3">
        <v-btn class="mx-4" variant="elevated">default</v-btn>
        <v-btn class="mx-4" variant="flat">flat</v-btn>
        <v-btn class="mx-4" variant="tonal">tonal</v-btn>
        <v-btn class="mx-4" variant="outlined">outlined</v-btn>
        <v-btn class="mx-4" variant="text">text</v-btn>
        <v-btn class="mx-4" variant="plain">plain</v-btn>
    </v-card>
    <v-card class="pa-4 ma-4 elevation-24">
        <v-btn class="mx-4" color="blue-accent-3" variant="outlined" size="small">outlined Button</v-btn>
        <v-btn class="mx-4" color="indigo-darken-1" variant="flat" border="0">Tile Button</v-btn>
    </v-card>
</template>

<script>
export default {

}
</script>

<style>

</style>