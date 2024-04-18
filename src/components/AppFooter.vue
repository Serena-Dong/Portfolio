<script></script>
<template>
    <footer>
        <div class="container-none">

            <h1 class="text-5xl font-bold uppercase">Let's Connect</h1>

            <!-- Links -->
            <ul class="flex flex-wrap gap-2">
                <li><a href="">Linkedin</a></li>
                <li><a href="">GitHub</a></li>
                <li><a href="">serenadong@outlook.it</a></li>
            </ul>

            <!-- Signature -->
            <ul class="flex flex-wrap justify-between gap-1">
                <li class="col text-xs">Made with <i class="fa-solid fa-heart"></i> and <i
                        class="fa-brands fa-vuejs"></i></li>
                <li class="col text-xs text-end"><i class="fa-solid fa-arrow-up"></i> Back to top</li>
                <li class="col text-xs">© 2024 Serena Dong</li>
            </ul>

        </div>
    </footer>
</template>
<style lang="scss" scoped>
@import "./../assets/scss/partials/_variables.scss";

footer {
    padding: $mobile-padding;

    .container-none>* {
        padding: calc($mobile-padding/2) 0;
    }
}
</style>