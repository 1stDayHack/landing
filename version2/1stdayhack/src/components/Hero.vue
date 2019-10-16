<template>
    <v-container fluid fill-height class="home-hero" style="max-height: 100vh;">
        <v-layout justify-center align-center column pa-5>
            <div class="display-4 font-weight-bold white--text text-xs-center">Highschoolers' Hackathon</div>
            <div class="display-4 font-weight-bold white--text text-xs-center mb-3">Learn by building softwares</div>
            <v-btn fab class="mt-5 blue">
                <v-icon large color="white">mdi-chevron-down</v-icon>
            </v-btn>
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'Hero'
};
</script>

<style scoped>
    .home-hero {
        background: url('~@/assets/images/hero-image.jpg');
        background-size: cover;
        width: 100%;
        height: 100%;
    }
</style>