<template>
    <v-container>
        <v-layout>
            <h1>Tracks</h1>
            <home-plans></home-plans>
            <meal-recipes></meal-recipes>
        </v-layout>
    </v-container>
</template>

<script>
import HomePlans from "@/components/HomePlans";
import MealRecipes from "@/components/MealRecipes";

export default {
    name: 'Tracks',
    components: {
        HomePlans,
        MealRecipes
    }
};
</script>

<style scoped>
</style>