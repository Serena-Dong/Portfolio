<script></script>
<template>
    <main>
        <div class="container-none">

            <section class="about-me">

                <!-- Content -->
                <div class="content">
                    <h1 class="text-4xl font-bold uppercase mb-3">About Me</h1>
                    <p class="text-xl">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reprehenderit, error
                        animi.
                        Ut praesentium pariatur aspernatur temporibus repudiandae? Molestias reprehenderit, iusto
                        dignissimos sequi ratione ullam rem dolores in deleniti hic blanditiis.</p>
                </div>

                <!-- Scroll
                <div class="scroll text-start">
                    <span class="text-sm">scroll more <i class="fa-solid fa-arrow-down"></i></span>
                </div> -->

            </section>

            <section class="Portfolio">
                <h1 class="text-4xl font-bold uppercase mb-3">Portfolio</h1>
                <p class="text-xl">Collection of my works, find more on my <a href="">GitHub <i
                            class="fa-solid fa-link"></i></a></p>
            </section>


        </div>
    </main>

</template>
<style lang="scss" scoped>
@import "./../assets/scss/partials/_variables.scss";

main {
    padding: $mobile-padding;

    section {
        padding: $mobile-margin 0;

        min-height: 100vh;
    }
}
</style>