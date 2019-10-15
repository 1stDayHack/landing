<template>
        <v-app-bar app color="blue accent-3" dark>
            <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
            <v-spacer class="d-block d-md-none"></v-spacer>
            <v-toolbar-title class="headline">
                <div class="pt-2 d-inline-block">
                    {{appTitle}}
                </div>
            </v-toolbar-title>
		    <v-spacer></v-spacer>
            <v-toolbar-items class="mx-2 d-none d-md-block">
                <v-btn text>About</v-btn>
                <v-btn text>Tracks</v-btn>
                <v-btn text>Schedule</v-btn>
                <v-btn text>Sponsorship</v-btn>
                <v-btn text>The Team</v-btn>

                <div class="d-inline-block">
                    <v-btn class="mx-2" color="pink accent-3">SIGN UP</v-btn>
                </div>
            </v-toolbar-items>

            <v-navigation-drawer app v-model="drawer" absolute temporary>
                <v-list dense>
                    <v-list-item v-for="(item, index) in items" :key="index">
                        <v-list-item-content>
                            {{item.title}}
                        </v-list-item-content>
                    </v-list-item>
                </v-list>
            </v-navigation-drawer>
        </v-app-bar>
</template>

<script>
export default {
    name: 'AppNavigation',
    data() {
        return {
            appTitle: '1stDayHack',
            drawer: false,
            items: [
                { title: 'About' },
                { title: 'Tracks' },
                { title: 'Schedule' },
                { title: 'Sponsorship' },
                { title: 'The Team' },
            ]
        };
    }
};
</script>

<style scoped>
</style>