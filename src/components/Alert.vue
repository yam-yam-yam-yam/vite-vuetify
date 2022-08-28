<template>
    <v-card class="pa-4 ma-4 elevation-24">
        <v-alert
            class="my-2"
            border
            border-color="red"
            closable
            close-icon="mdi-checkbox-marked-circle"
            icon="mdi-firework"
        >
            Suspendisse enim turpis, dictum sed, iaculis a, condimentum nec, nisi. Vivamus quis mi. Quisque ut nisi. Maecenas malesuada.
        </v-alert>
        <p>border</p>
        <p>border-color="red"</p>
        <p>closable</p>
        <p>close-icon="mdi-checkbox-marked-circle"</p>
        <p>icon="mdi-firework"</p>
    </v-card>
    <v-card class="pa-4 ma-4 elevation-24">
        <v-alert
            class="my-2"
            density="compact"
            title="title"
        >
            density="compact"
        </v-alert>
        <v-alert
            class="my-2"
            density="comfortable"
            title="title"
        >
            density="comfortable"
        </v-alert>
        <v-alert
            class="my-2"
            density="default"
            title="title"
        >
            density="default"
        </v-alert>
    </v-card>
    <v-card class="pa-4 ma-4 elevation-24">
        <v-alert
            class="my-2"
            prominent
            icon="mdi-firework"
            max-width="500"
            max-height="500"
            position="relative"
            color="red-darken-4"
        >
            Suspendisse enim turpis, dictum sed, iaculis a, condimentum nec, nisi. Vivamus quis mi. Quisque ut nisi. Maecenas malesuada.
        </v-alert>
        <p>prominent (큰 아이콘)</p>
        <p>icon="mdi-firework"</p>
        <p>max-width="500"</p>
        <p>max-height="500"</p>
        <p>position="relative"</p>
        <p>color="red-darken-4"</p>
        <p>class="bg-teal-darken-4 text-red-darken-4" (이렇게도 사용 가능)</p>
    </v-card>
    <v-card class="pa-4 ma-4 elevation-24">
        <v-alert
            class="my-2"
            prominent
            icon="mdi-firework"
            max-width="500"
            max-height="500"
            position="relative"
            color="red-darken-4"
        >
            Suspendisse enim turpis, dictum sed, iaculis a, condimentum nec, nisi. Vivamus quis mi. Quisque ut nisi. Maecenas malesuada.
        </v-alert>
        <p>prominent (큰 아이콘)</p>
        <p>icon="mdi-firework"</p>
        <p>max-width="500"</p>
        <p>max-height="500"</p>
        <p>position="relative"</p>
        <p>color="red-darken-4"</p>
        <p>class="bg-teal-darken-4 text-red-darken-4" (이렇게도 사용 가능)</p>
    </v-card>
    <v-card class="pa-4 ma-4 elevation-24">
        <v-alert
            class="my-2"
            variant="elevated"
            tag="span"
        >
            variant="elevated"(default)
        </v-alert>
        <v-alert
            class="my-2"
            variant="flat"
        >
            variant="flat"        
        </v-alert>
        <v-alert
            class="my-2"
            variant="tonal"
        >
            variant="tonal"        
        </v-alert>
        <v-alert
            class="my-2"
            variant="outlined"
        >
            variant="outlined"        
        </v-alert>
        <v-alert
            class="my-2"
            variant="text"
        >
            variant="text"        
        </v-alert>
        <v-alert
            class="my-2"
            variant="plain"
        >
            variant="plain"        
        </v-alert>
    </v-card>
</template>

<script>
export default {
    data() {
        return {
            
        }
    },
}
</script>

<style>

</style>