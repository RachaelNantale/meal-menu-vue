<template>
    <v-container fluid fill-height class="home-hero" style="max-height: 100vh;">
        <v-layout justify-center align-center column pa-5>
            <div class="display-4 font-weight-black gold--text text-xs-center">
                HEALTHY MEALS
            </div>
            <div
                class="display-4 font-weight-black gold--text text-xs-center mb-3"
            >
                FOR YOUR TABLE
            </div>
            <div class="display-1 font-weight-bold gold--text text-xs-center">
                Finally be a foodie at home with fresh, chef-prepared meals
                delivered daily to your door.
            </div>
            <v-btn fab class="mt-5 brown darken-4">
                <v-icon large color="gold">expand_more</v-icon>
            </v-btn>
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'HomeHero'
};
</script>

<style scoped>
.home-hero {
    background: url('http://source.unsplash.com/08bOYnH_r_E');
    background-size: cover;
    width: 100%;
    height: 100%;
}
</style>
