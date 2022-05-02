<template>
    <div class="bg_section pb-5">
        <div class="container d-flex ">
            <div class="bg-crossfit d-flex  ">
                <div class="bg_dark d-flex align-items-end ">
                    <div class="text-white ms-3">
                        <img class="w-25" src="../assets/img/icons8-acquario-50 (3).png" alt="">
                        <h5>Crossfit works with</h5>
                        <p>Push your limits</p>
                    </div>
                </div>

            </div>
            <div class="bg-gym ms-4  d-flex">
                <div class="bg_dark d-flex align-items-end">
                    <div class=" text-white ms-3">
                        <img class="w-25" src="../assets/img/icons8-acquario-50 (3).png" alt="">
                        <h5>New gym apparel</h5>
                        <p>Look good, feel good</p>
                    </div>
                </div>

            </div>
            <div class="bg-training ms-4 d-flex">
                <div class="d-flex align-items-end bg_dark">
                    <div class="text-white ms-3">
                        <img class="w-25" src="../assets/img/icons8-acquario-50 (3).png" alt="">
                        <h5>Team training</h5>
                        <p>Find a partner</p>
                    </div>
                </div>

            </div>
            
        </div>
        <div class=" container text-center mt-5 width_custom text-white pb-5">
                <h5>"Now you respond to the challenge in the second half will determine what you become after the game, whether you are a winner or a loser."</h5>
                <img src="../assets/img/icons8-acquario-50 (1).png" alt="">
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
        background: linear-gradient(to bottom right, #0f17dd , #6b0c7a , #bc0428);
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
    .bg-crossfit:hover{
        width: 280px;
        height: 280px;
    }
    .bg_dark {
        background-color: rgba(0,0,0,0.30);
        background-size: cover;
        height: 250px;
        width: 250px;
        border-radius: 0 0 20px 0;
    }
    .bg_dark:hover{
        width: 280px;
        height: 280px;
    }
    .bg-gym {
        background-image: url('../assets/img/box1-2x.jpg');
        background-size: cover;
        height: 250px;
        width: 250px;
        border-radius: 0 0 20px 0;
        margin-top: -40px;
    }
    .bg-gym:hover{
        width: 280px;
        height: 280px;
    }
    .bg-training {
        background-image: url('../assets/img/box3-2x.jpg');
        background-size: cover;
        height: 250px;
        width: 250px;
        border-radius: 0 0 20px 0;
        margin-top: -40px;
    }
    .bg-training:hover{
        width: 280px;
        height: 280px;
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