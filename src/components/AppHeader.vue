<script setup>
import Jumbotron from './contents/Jumbotron.vue'
</script>
<template>
    <header>
        <nav class="container-none flex justify-between">

            <!-- Functions -->
            <div class="col functions">
                <ul class="flex flex-col gap-3  m-0">
                    <li><a href="">About</a></li>
                    <li><a href="">Works</a></li>
                    <li><a href="">Contacts</a></li>
                </ul>
            </div>

            <!-- Light/Dark Mode -->
            <div class="col">
                <p class="m-0 font-bold"><i class="fa-regular fa-sun"></i> Light</p>
                <!-- <p class="m-0 font-bold"><i class="fa-solid fa-moon"></i> Dark</p> -->
            </div>
        </nav>

        <!-- <jumbotron></jumbotron> -->
    </header>
</template>
<style lang="scss" scoped>
@import "./../assets/scss/partials/variables";

header {
    padding: $mobile-padding;

    border: 1px solid black;
}
</style>