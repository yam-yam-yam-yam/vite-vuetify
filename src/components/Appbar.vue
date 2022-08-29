<template>
    <v-app-bar
        location="bottom"
        color="primary" 
        :collapse="collapse"
        density="compact"
    >
        <template v-slot:prepend>
            <v-app-bar-nav-icon icon="fa-solid fa-broom" @click="collapse=!collapse"></v-app-bar-nav-icon>
        </template>
        <v-app-bar-title>v-app-bar-title tag</v-app-bar-title>
        <template v-slot:append>
            <v-btn icon="fa-solid fa-circle-chevron-down"></v-btn>
        </template>
    </v-app-bar>
    <p>v-app-bar 태그는 prepend, append slot을 가지고 있음</p>
    <p>collapse 속성 적용 가능</p>
</template>

<script>
export default {
    data() {
        return {
            collapse:false
        }
    },
}
</script>

<style>

</style>