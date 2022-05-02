<template>
    <div class="d-flex justify-content-between align-center">
        <div class="bg_section  ">
            <div class="bg_dark d-flex justify-content-center align-items-center">
                <PlayerComp />
            </div>

        </div>
        <div class="d-flex w-100 mt-5">
            <div class="mt-5 px-5">
                <a href="#">Tune up your workout</a>
                <h1 class="me-5 mt-4">The best health & fitness advide online</h1>
                <div class="d-flex align-items-center mt-4">
                    <img src="../assets/img/unnamed.jpg" alt="logo unnamed">

                    <div class="d-flex flex-column ps-3">
                        <h6 class=" ">ThemeFusion</h6>
                        <div class="bg-danger w_custom  text-white d-flex  border align-items-center">
                            <i class="fa-brands fa-youtube  ms-2 "> </i>
                            <span class="ps-2">YouTube</span>
                            <div class=" ms-4 px-1 bg_custom text-dark ">
                                <span>999+</span>
                            </div>
                        </div>

                    </div>
                </div>
                <p class="mt-4">Arcu eu facilisi ut quisque placerat nunc habitant. Magna semper mauris, venenatis, leo
                    integer sit pellentesque.</p>
                <button class="bg-danger text-white px-3 py-2 rounded-pill mt-4 blue">
                    <i class="fa-brands fa-youtube  me-2"></i>
                    Visit my YouTube channel
                </button>
            </div>

        </div>

    </div>
</template>

<script>
    import PlayerComp from "./PlayerComp"
    export default {
        name: 'SectionVideo',
        components: {
            PlayerComp
        }
    }
</script>

<style scoped lang="scss">
    .bg_section {
        background-image: url('../assets/img/service15-2x.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        width: 100%;
        height: 650px;
        border-radius: 0 0 30px 0;
        margin-top: -40px;
    }

    .bg_dark {
        background-color: rgb(0, 0, 0);
        background-color: rgba(0, 0, 0, 0.3);
        background-size: cover;
        background-repeat: no-repeat;
        width: 100%;
        height: 650px;
        border-radius: 0 0 30px 0;
    }

    a {
        text-decoration: none;
    }

    .w_custom {
        width: 160px;
    }

    .bg_custom {
        background-color: rgb(249, 249, 249);
    }
    .blue:hover{
        background-color: lightblue;
    }
</style>