<template>
    <div class="container mt-5">
        <div class="d-flex justify-content-between align-items-center py-3">
           <h4>Featured playlist</h4> 
           <h5>View all videos <i class="fa-solid fa-angle-right"></i></h5>
        </div>
        
        <div class="mb-5">
            <div class="container d-flex">
                <div>
                    <div class="bg-glute d-flex justify-content-center align-items-center">
                        <div class=" d-flex align-items-center">
                            <PlayerComp />
                        </div>
                    </div>
                    <div class="text-center mt-3">
                        <h5>Things & glute workout</h5>
                        <a href="#">Increase your mobility</a>
                    </div>
                </div>
                
                <div>
                    <div class="bg-lift d-flex justify-content-center align-items-center ms-4">
                        <div class="d-flex align-items-center">
                            <PlayerComp />
                        </div>
                    </div>
                    <div class="text-center mt-3">
                        <h5>Lift, firm & perk up</h5>
                        <a href="#">Feel young again</a>
                    </div>
                </div>
                <div>
                    <div class="bg-slim ms-4 d-flex justify-content-center align-items-center">
                        <div class="d-flex align-items-center">
                            <PlayerComp />
                        </div>
                    </div>
                    <div class="text-center mt-3">
                        <h5>Slim & trim your waist</h5>
                        <a href="#">Shed those extra pounds</a>
                    </div>
                </div>
                

            </div>
        </div>
    </div>
</template>

<script>
    import PlayerComp from './PlayerComp.vue'
    export default {
        name: 'VideoComp',
        components: {
            PlayerComp
        }
    }
</script>

<style scoped lang="scss">
    .bg-glute {
        background-image: url('../assets/img/video2-2x.jpg');
        background-size: contain;
        background-repeat: no-repeat;
        width: 320px;
        height: 200px;
        border-radius: 0 0 20px 0;
    }

    .bg-lift {
        background-image: url('../assets/img/video7-2x.jpg');
        background-size: contain;
        background-repeat: no-repeat;
        width: 320px;
        height: 200px;
        border-radius: 0 0 20px 0;
    }

    .bg-slim {
        background-image: url('../assets/img/video9-2x.jpg');
        background-size: contain;
        background-repeat: no-repeat;
        width: 320px;
        height: 200px;
        border-radius: 0 0 20px 0;
    }
    a{
        text-decoration: none;
    }
</style>