<script>
export default {
    name: 'AppHero',
    data() {
        return {

        }
    },
    methods() {

    }
}
</script>

<template>
    <div class="jumbotron">
        <img src="../assets/Sfondi-natalizi.jpg" alt="Christmas-background-image" srcset="">
        <h1 class="title-apphero">Io sono il title nell'AppHero</h1>
    </div>
</template>

<style scoped>
.jumbotron {
    position: relative;
    width: 700px;
    margin: 0 auto;
}

.jumbotron img {
    width: 100%;
}

h1.title-apphero {
    position: absolute;
    top: 20%;
    left: 30%;
    transform: translate(-50%, -50%);
    text-align: center;
    margin: 0;
    padding: 20px;
    font-size: 3rem;
}
</style>
