<template>
    <div class="bg_section pb-5">
        <div class="container d-flex ">
            <div class="bg-crossfit d-flex  ">
                <div class="bg_dark d-flex align-items-end ">
                    <div class="text-white z-index">
                        <h5>Crossfit works with</h5>
                        <p>Push your limits</p>
                    </div>
                </div>

            </div>
            <div class="bg-gym ms-4  d-flex">
                <div class="bg_dark d-flex align-items-end">
                    <div class=" text-white ">
                        <h5>Crossfit works with</h5>
                        <p>Push your limits</p>
                    </div>
                </div>

            </div>
            <div class="bg-training ms-4 d-flex">
                <div class="d-flex align-items-end bg_dark">
                    <div class="text-white">
                        <h5>Crossfit works with</h5>
                        <p>Push your limits</p>
                    </div>
                </div>

            </div>
            
        </div>
        <div class=" container text-center mt-5 width_custom text-white pb-5">
                <h5>"Now you respond to the challenge in the second half will determine what you become after the game, whether you are a winner or a loser."</h5>
                <div class="pt-4">
                    <img class="rounded-circle w_custom" src="../assets/img/avatar-1-2x.jpg" alt="">
                    <span class="px-3">Brad Johnson</span>
                    <span class="light-grey">Las Vegas</span>
                </div>
        </div>
    </div>

</template>

<script>
    export default {
        name: 'Sezione1Comp',
        components: {

        }
    }
</script>

<style scoped lang="scss">
     .light-grey {
        color: lightgrey;
    }
    .bg_section {
        background: linear-gradient(165deg, #0f17dd , #690d7e 70%, #b4042d);
    }

    .bg-crossfit {
        background-image: url('../assets/img/service6-2x.jpg');
        background-size: cover;
        height: 250px;
        width: 250px;
        border-radius: 0 0 20px 0;
        margin-top: -40px;
        z-index: 1;
    }

    .bg_dark {
        background-color: black;
        background-size: cover;
        opacity: 0.2;
        height: 250px;
        width: 250px;
        border-radius: 0 0 20px 0;
       
    }

    .bg-gym {
        background-image: url('../assets/img/box1-2x.jpg');
        background-size: cover;
        height: 250px;
        width: 250px;
        border-radius: 0 0 20px 0;
        margin-top: -40px;
    }

    .bg-training {
        background-image: url('../assets/img/box3-2x.jpg');
        background-size: cover;
        height: 250px;
        width: 250px;
        border-radius: 0 0 20px 0;
        margin-top: -40px;
    }

    p {
        color: yellow;
        font-weight: bold;
    }

    .z-index {
        z-index: 1;
        opacity: 2;
    }
    .width_custom{
        width: 35%;
    }
    .w_custom{
        width: 60px;
    }
</style>