<template>
    <div class=" ">
        <div class="bg_section bg_gradient d-flex justify-content-center align-items-center">
            <div class="container text-white text-center w-50 px-4">
                <PlayerComp class="player" />
                <h1>Crossfit workout of the day</h1>
                <h4 class="my-3">November 15th, 2019</h4>
                <p>View all videos <i class="fa-solid fa-arrow-right-long"></i></p>
            </div>
        </div>

    </div>
</template>

<script>
    import PlayerComp from './PlayerComp.vue'
    export default {
        //Cambiare il nome con quello del componente creato
        name: 'CrossfitComp',
        components: {
            PlayerComp
        }
    }
</script>

<style scoped lang="scss">
    .bg_section {
        background-image: url('../assets/img/banner14-2x.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        height: 600px;
    }

    .bg_gradient {
        background-image:linear-gradient(rgba(66,87,239,0.5) rgba(70,19,160,0.5) rgba(160,6,68,0.5) ) ;
        opacity:0.5;
        background-size: cover;
        background-repeat: no-repeat;
        height: 600px;
       
    }

    .fa-angle-right {
        font-size: 0.7em;
    }

    h4 {
        color: yellow;
    }

    .player {
        margin: 0 auto;
    }
</style>