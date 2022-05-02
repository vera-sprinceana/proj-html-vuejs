<template>
    <div class="bg_hero">
        <div class="container_custom  py-5 d-flex justify-content-between align-items-center">
            <div class="d-flex">
                <div class="py-5">
                    <p class="text-danger mt-3">Join our mailing list today</p>
                    <h1 class="text-white w-75">Insider offers & flash sales in your inbox every week.</h1>
                    <img src="../assets/img/icons8-acquario-50 (1).png" alt="">
                    <div class="pt-5">
                        <input class="rounded-pill p-2 w-50" type="text" placeholder="Insert your email...*">
                        <button class="btn bg-primary  light-grey rounded-pill px-4 ms-3 red">Subscribe </button>
                        <p class="w-75 light-grey mt-4">Curabitur non nulla sit amet nisl tempus convallis quis ac
                            lectus dolor sit amet, consectetur adipiscing elit sed porttitor lectus.</p>
                    </div>
                </div>

            </div>

        </div>
    </div>
</template>

<script>
    export default {
        name: 'SectionTwo',
        components: {

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
        background-image: url('../assets/img/banner1-2x.jpg');
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
    .red:hover{
        background-color: #bc0428;
        color: black;
    }
</style>