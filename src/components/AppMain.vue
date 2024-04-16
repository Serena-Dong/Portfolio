<script></script>
<template>
    <main class="rounded-bottom-5 py-5">
        <div class="container">
            <section class="row gap-1 mb-4">
                <div class="col-12">
                    <a href="">
                        <img src="" alt=""></a>
                </div>
            </section>
            <section class="row gap-4 justify-content-between mb-4">
                <div class="col">
                    <a href="">
                        <img src="" alt=""></a>
                </div>
                <div class="col-4">
                    <a href="">
                        <img src="" alt=""></a>
                </div>
            </section>
            <section class="row gap-4 justify-content-between mb-4">
                <div class="col">
                    <p><b>My Skills</b></p>
                    <ul class="p-0">
                        <li>Html, Css and Javascript</li>
                        <li>Vue.js, SASS, SCSS</li>
                        <li>PHP, PhPMyAdmin</li>
                        <li>MySQL & SQL</li>
                        <li>Laravel</li>
                        <li>GitHub</li>
                        <li>Suite Adobe</li>
                    </ul>
                </div>
                <div class="col-7">

                    <p class="fs-2">Studied Web Development at <span class="rounded-2 ">Boolean Careers</span>. And
                        have been working in the tech
                        industry for
                        over a year.</p>


                    <div class="d-flex justify-content-between align-items-center mt-5">
                        <p class="col-8">My passion for coding started when I was young, and I have pursued this passion by
                            studying by my own over the years. With an artistic background, I have combined my visual
                            skills and coding skills
                            to
                            build and create user interfaces for websites, software applications, and mobile
                            apps.</p>
                        <div class="col-2">
                            <a class="btn" href="">Read More</a>
                        </div>
                    </div>
                </div>
            </section>
        </div>
    </main>
</template>
<style scoped lang="scss">
main {
    background-color: rgb(238, 238, 238);

    img {
        object-fit: cover;
        width: 100%;

        border-radius: 3rem;

        &:hover {
            transform: scale(1.02);
            transition: transform 0.25s;
        }
    }

    .row>* {

        cursor: pointer;

    }

    ul li {
        list-style: none;
    }

    .btn {
        border: 1px solid black;
        border-radius: 3rem;

        &:hover {
            transform: scale(1.1);
            transition: transform 0.25s;

            border: 1px solid black;
        }
    }
}
</style>