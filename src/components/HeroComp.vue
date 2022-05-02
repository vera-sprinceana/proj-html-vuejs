<template>
    <div class="bg_hero">
        <div class="container_custom  py-5 d-flex justify-content-between align-items-center">
            <div class="d-flex">
                <div class="py-5">
                    <h5 class="text-danger mt-3">Certified fintess professional</h5>
                    <h1 class="text-white">Take control of your health</h1>
                    <img class="my-3" src="../assets/img/icons8-acquario-50 (1).png" alt="">
                    <p class="grey">Curabitur non nulla sit emet nisl tempus convallis quis ac lectus
                        dolor sit amet.</p>
                    <div class="py-5">
                        <button class="btn btn-primary me-4 rounded-pill red"><i class="fa-brands fa-youtube"></i> 
                        Visit my YouTube channel
                        </button>
                        <button class=" btn bg-dark text-white rounded-pill px-3 white">
                            Buy Avada today 
                            <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                </div>

            </div>
            <PlayerComp />
        </div>
    </div>
</template>

<script>
    import PlayerComp from './PlayerComp.vue'
    export default {
        name: 'HeroComp',
        components: {
            PlayerComp
        }
    }
</script>

<style scoped lang="scss">
    .container_custom {
        width: 80%;
        margin: 0 auto;
        padding: 10px 0;
    }

    .bg_hero {
        background-image:url('../assets/img/slider82x-scaled.jpg');
        background-size: cover;
        background-repeat: no-repeat;
    }

    .grey {
        color: lightgrey;
    }

    .fa-arrow-right {
        font-size: 0.8em;
    }

    .fs_custom {
        font-size: 0.8em;
    }
    .red:hover{
        background-color: #ff414b;
    }
    .white:hover{
        background-color: #f2f2f2;
        color: rgb(0, 0, 0);
    }
</style>