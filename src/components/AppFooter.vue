<script></script>
<template>
    <footer class=" text-white">
        <div class="container">

            <!-- Upper -->
            <div class="footer-up py-5">
                <div class="row justify-content-between">

                    <!-- Title -->
                    <div class="col">
                        <p>Portofolio 2022-2023</p>
                    </div>
                    <!-- Name -->
                    <div class="col text-center">
                        <p>Serena Dong</p>
                    </div>
                    <!-- Coordinates -->
                    <div class="col text-end">
                        <p>
                            52.7904'' N, 18.7440'' E
                        </p>
                    </div>
                </div>
            </div>

            <!-- Middle -->
            <div class="footer-middle py-5 my-5 text-center">
                <h1><a href="">Get in touch</a></h1>
            </div>

            <!-- Lower -->
            <div class="footer-lower pt-5 pb-4 ">
                <div class="row justify-content-between">

                    <!-- Copyrights -->
                    <div class="col-3">
                        <span>© All rights reserved. Template by Vlad Sokur
                            Powered by Webflow</span>
                    </div>

                    <!-- Functions -->
                    <div class="col-3">
                        <nav>
                            <ul class="d-flex gap-3 justify-content-center ">
                                <li><a href="https://www.linkedin.com/in/serena-dong-500877240/">Linkedin</a></li>
                                <li><a href="https://github.com/Serena-Dong">GitHub</a></li>
                            </ul>
                        </nav>
                    </div>
                    <div class="col-3"></div>
                </div>

            </div>
        </div>
    </footer>
</template>
<style scoped>
.footer-middle h1 a {
    color: white;
}

.footer-middle h1 a:hover {
    font-size: 3.5rem;

    transition-duration: 300ms;
    transition-property: font-size;
}

.footer-up,
.footer-lower span {
    font-size: 0.8rem;
}

.footer-lower nav ul li a {
    color: white;
    padding: 0.5rem 1rem;
    border: white 1px solid;
    border-radius: 3rem;
}

.footer-lower nav ul li a:hover {
    color: black;
    background-color: white;

    transition-duration: 1s;
    transition-property: background-color;
}
</style>