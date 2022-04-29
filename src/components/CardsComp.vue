<template>
    <div class="bg-dark">
        <div class="container d-flex justify-content-between text-white py-3 ">
            <div class="border_primary w-25 text-center p-3">
                <img class="my-5" src="../assets/img/icons8-smartwatch-64.png" alt="">
                <h5>Team trainig</h5>
                <h6 class="text-yellow">Find a partner</h6>
                <p>Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget
                    sed dius vehicula. Tristique.</p>
                <p>Find a partner <i class="fa-solid fa-angle-right"></i></p>
            </div>
            <div class="border_primary w-25 text-center p-3">
                <img class="my-5" src="../assets/img/icons8-bilanciere-50.png" alt="">
                <h5>Crossfit workout</h5>
                <h6 class="text-yellow">Push your limits</h6>
                <p>Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget
                    sed dius vehicula. Tristique.</p>
                <p>Learn about Crossfit <i class="fa-solid fa-angle-right"></i></p>
            </div>
            <div class="border_primary w-25 text-center p-3">
                <i class="fa-solid fa-arrow-right"></i>
                <img class="my-5" src="../assets/img/icons8-torso-della-donna-64.png" alt="">
                <i class="fa-solid fa-arrow-left"></i>
                <h5>Weight loss plan</h5>
                <h6 class="text-yellow">Find a partner</h6>
                <p>At laoreet senectus volutpat diam vel sed sed amet pellentesque. Lobortis ut aliquam risus purus. A
                    tellus ut etiam.</p>
                <p>Schedule a workout <i class="fa-solid fa-angle-right"></i></p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'App',
        components: {

        }
    }
</script>

<style scoped lang="scss">
    img {
        width: 60px;
    }

    .border_primary {
        border: 3px solid rgb(29, 29, 164);
        border-radius: 5px;
    }

    .text-yellow {
        color: yellow;
    }
</style>