<script setup>
import Jumbotron from './contents/Jumbotron.vue'
</script>
<template>
    <header>
        <nav class="container-none flex justify-between">

            <!-- Functions -->
            <div class="col functions">
                <ul class="flex flex-col gap-3 m-0 md:flex-row">
                    <li><a href="">About me</a></li>
                    <li><a href="">Portfolio</a></li>
                    <li><a href="">Contacts</a></li>
                </ul>
            </div>

            <!-- Light/Dark Mode -->
            <div class="col">
                <p class="m-0 font-bold"><i class="fa-regular fa-sun"></i> Light</p>
                <!-- <p class="m-0 font-bold"><i class="fa-solid fa-moon"></i> Dark</p> -->
            </div>
        </nav>

        <!-- Jumbotron -->
        <jumbotron></jumbotron>

        <!-- Scroll -->
        <div class="scroll text-end">
            <span class="text-sm">scroll more <i class="fa-solid fa-arrow-down"></i></span>
        </div>

    </header>
</template>
<style lang="scss" scoped>
@import "./../assets/scss/partials/variables";

header {
    padding: $mobile-padding;


    height: 100vh;

    nav {
        height: 20%;
    }

    .jumbotron {
        height: 75%;
    }

    .scroll {
        height: 5%;
    }
}
</style>