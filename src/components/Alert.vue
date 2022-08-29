<template>
    <v-card class="pa-4 ma-4 elevation-24">
        <v-alert
            class="my-2"
            border
            border-color="red"
            closable
            close-icon="fas fa-home"
            icon="fas fa-home"
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
            icon="fas fa-home"
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
    <v-card class="pa-4 ma-4 elevation-24">
        <v-alert
            class="my-2"
            closable
        >
            <template v-slot:append>
                v-slot:apeend
            </template>
            <template v-slot:prepend>
                v-slot:prepend
            </template>
            <template v-slot:close>
                <v-icon icon="fas fa-home"></v-icon>
            </template>
            Suspendisse enim turpis, dictum sed, iaculis a, condimentum nec, nisi. Vivamus quis mi. Quisque ut nisi. Maecenas malesuada.
        </v-alert>
    </v-card>
    <v-card class="pa-4 ma-4 elevation-24">
        <v-alert
            class="my-2"
            closable
            v-model="close"
        >
            Suspendisse enim turpis, dictum sed, iaculis a, condimentum nec, nisi. Vivamus quis mi. Quisque ut nisi. Maecenas malesuada.
        </v-alert>
        <v-btn class="my-2" @click="close=!close">버튼</v-btn>
        <p>v-model="close"</p>
    </v-card>
    <v-card class="pa-4 ma-4 elevation-24">
        <v-alert
            color="blue-grey-darken-4 my-2"
            icon="fa-solid fa-fire"
            variant="elevated"
            density="comportable"
            closable
        >
            Suspendisse enim turpis, dictum sed, iaculis a, condimentum nec, nisi. Vivamus quis mi. Quisque ut nisi. Maecenas malesuada.
        </v-alert>
        <v-alert
            color="blue-grey-darken-4 my-2"
            icon="fa-solid fa-fire"
            variant="tonal"
            density="comportable"
            closable
        >
            Suspendisse enim turpis, dictum sed, iaculis a, condimentum nec, nisi. Vivamus quis mi. Quisque ut nisi. Maecenas malesuada.
        </v-alert>
        <v-alert
            color="light-blue-accent-2 my-2"
            icon="fa-solid fa-fire"
            variant="tonal"
            density="comportable"
            border
            closable
        >
            Suspendisse enim turpis, dictum sed, iaculis a, condimentum nec, nisi. Vivamus quis mi. Quisque ut nisi. Maecenas malesuada.
        </v-alert>
        <v-alert
            color="pink-darken-1 my-2"
            icon="fa-solid fa-fire"
            variant="flat"
            density="comportable"
            border="end"
            closable
        >
            Suspendisse enim turpis, dictum sed, iaculis a, condimentum nec, nisi. Vivamus quis mi. Quisque ut nisi. Maecenas malesuada.
        </v-alert>
        <p>예제</p>
    </v-card>
</template>

<script>
export default {
    data() {
        return {
            close:true
        }
    },
}
</script>

<style>

</style>