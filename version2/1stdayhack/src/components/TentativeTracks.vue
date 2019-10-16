<template>
    <v-container grid-list-lg>
        <v-layout row>
            <v-flex xs12 class="text-xs-center display-1 font-weight-black my-5">Available Meal Plans</v-flex>
        </v-layout>

        <v-layout row wrap>
            <v-flex xs12 sm12 md4>
                <v-card>
                    <v-responsive>
                        <v-img src="~@/assets/images/sample1.jpg" height="500px">
                            <v-container fill-height fluid>
                                <v-layout fill-height>
                                    <v-flex xs12 align-end flexbox>
                                        <span class="headline white--text">Sample 1</span>
                                    </v-flex>
                                </v-layout>
                            </v-container>
                        </v-img>

                        <v-card-title primary-title>
                            <div>
                                <h3 class="headline mb-0">Sample 1</h3>
                                <div>
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum accusamus rem a labore officiis ratione ad sapiente dolorem reprehenderit? Facere adipisci aut harum a maiores quod numquam odit provident nam?
                                </div>
                            </div>
                        </v-card-title>

                        <v-card-actions v-if="['tracks'].includes($route.name)">
                            <v-btn outlined block color="blue" @click="showRecipes('paleo')">Select this plan</v-btn>
                        </v-card-actions>
                    </v-responsive>
                </v-card>
            </v-flex>

            <v-flex xs12 sm12 md4>
                <v-card>
                    <v-responsive>
                        <v-img src="~@/assets/images/sample1.jpg" height="500px">
                            <v-container fill-height fluid>
                                <v-layout fill-height>
                                    <v-flex xs12 align-end flexbox>
                                        <span class="headline white--text">Sample 1</span>
                                    </v-flex>
                                </v-layout>
                            </v-container>
                        </v-img>

                        <v-card-title primary-title>
                            <div>
                                <h3 class="headline mb-0">Sample 1</h3>
                                <div>
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum accusamus rem a labore officiis ratione ad sapiente dolorem reprehenderit? Facere adipisci aut harum a maiores quod numquam odit provident nam?
                                </div>
                            </div>
                        </v-card-title>

                        <v-card-actions v-if="['tracks'].includes($route.name)">
                            <v-btn outlined block color="blue" @click="showRecipes('vegan')">Select this plan</v-btn>
                        </v-card-actions>
                    </v-responsive>
                </v-card>
            </v-flex>

            <v-flex xs12 sm12 md4>
                <v-card>
                    <v-responsive>
                        <v-img src="~@/assets/images/sample1.jpg" height="500px">
                            <v-container fill-height fluid>
                                <v-layout fill-height>
                                    <v-flex xs12 align-end flexbox>
                                        <span class="headline white--text">Sample 1</span>
                                    </v-flex>
                                </v-layout>
                            </v-container>
                        </v-img>

                        <v-card-title primary-title>
                            <div>
                                <h3 class="headline mb-0">Sample 1</h3>
                                <div>
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum accusamus rem a labore officiis ratione ad sapiente dolorem reprehenderit? Facere adipisci aut harum a maiores quod numquam odit provident nam?
                                </div>
                            </div>
                        </v-card-title>

                        <v-card-actions v-if="['tracks'].includes($route.name)">
                            <v-btn outlined block color="blue" @click="showRecipes('keto')">Select this plan</v-btn>
                        </v-card-actions>
                    </v-responsive>
                </v-card>
            </v-flex>
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'TentativeTracks'
};
</script>

<style scoped>
</style>