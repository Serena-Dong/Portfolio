<script>
export default {
    name: 'Jumbotron'
}
</script>
<template>
    <div class="jumbotron container-none uppercase">
        <div class="title">
            <h1>Serena Dong</h1>
            <p>Full Stack Web Developer</p>
        </div>
        <div class="content">
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sunt consequatur, optio voluptate iusto, nemo
                natus deleniti excepturi beatae non obcaecati totam eius facilis ipsa eum maxime temporibus nihil
                adipisci quaerat.</p>
        </div>
    </div>
</template>
<style scoped lang="scss">
.jumbotron {

    .title {
        h1 {
            font-size: 8rem;
            font-weight: 600;
            margin: 0;
        }

        p {
            margin: 0;

            font-size: 5rem;
            font-weight: 600;
        }

    }

    .content {
        width: 60%;
    }
}
</style>