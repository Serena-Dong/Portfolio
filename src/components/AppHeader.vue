<script setup>
import Jumbotron from './contents/Jumbotron.vue'
</script>
<template>
    <header>
        <nav class="container-none flex justify-between">
            <!-- Name -->
            <div class="col">
                <p class="m-0 font-bold">Serena</p>
            </div>

            <!-- Functions -->
            <div class="col functions">
                <ul class="flex flex-col gap-3  m-0">
                    <li><a href="">about</a></li>
                    <li><a href="">portfolio</a></li>
                    <p class="m-0 font-bold"><i class="fa-regular fa-sun"></i> Light</p>
                </ul>
            </div>


            <!-- Light/Dark Mode
            <div class="col">
                <p class="m-0 font-bold"><i class="fa-regular fa-sun"></i> Light</p>
                <p class="m-0 font-bold"><i class="fa-solid fa-moon"></i> Dark</p>
            </div> -->
        </nav>

        <!-- <jumbotron></jumbotron> -->
    </header>
</template>
<style lang="scss" scoped>
header {
    border: 1px solid black;

    padding: 2rem;

    nav {
        margin-bottom: 3rem;
    }
}
</style>