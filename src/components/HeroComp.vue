<template>
    <div class="bg_hero">
        <div class="container_custom  py-5 d-flex justify-content-between align-items-center">
            <div class="d-flex">
                <div class="py-5">
                    <p class="text-danger mt-3">Certified fintess professional</p>
                    <h1 class="text-white">Take control of your health</h1>
                    <p class="light-grey fs_custom">Curabitur non nulla sit emet nisl tempus convallis quis ac lectus
                        dolor sit amet.</p>
                    <div class="py-5">
                        <button class="btn btn-primary me-4 rounded-pill"><i class="fa-brands fa-youtube"></i> 
                        Visit my YouTube channel
                        </button>
                        <button class="bg-dark  light-grey rounded-pill px-2">
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
        background-image: url('../assets/img/slider82x-scaled.jpg');
        background-size: cover;
        background-repeat: no-repeat;
    }

    .light-grey {
        color: lightgrey;
    }

    .fa-arrow-right {
        font-size: 0.8em;
    }

    .fs_custom {
        font-size: 0.8em;
    }
</style>