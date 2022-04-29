<template>
    <div class="bg_section d-flex justify-content-center align-items-center ">
        <div class="container text-white text-center w-50 px-4">
            <h1>"I've failed over and over again in my life. And that is why I succeed."</h1>
            <p>Arcu auctor gravida nisl, conque sit nisi tincidunt eget proin. In lacinia lacus donec sed massa in ipsum
                eros, tristique. Gravida suspendisse etiam in iaculis</p>
            <button class="btn btn-primary  light-grey rounded-pill px-4">
                Buy Avada today
                <i class="fa-solid fa-angle-right"></i>
            </button>
        </div>
    </div>
</template>

<script>
    export default {
        //Cambiare il nome con quello del componente creato
        name: 'MegaSection',
    }
</script>

<style scoped lang="scss">
    .bg_section {
        background-image: url('../assets/img/banner2-2x.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        height: 600px;
    }

    .fa-angle-right {
        font-size: 0.7em;
    }
</style>