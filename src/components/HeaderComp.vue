<template>
    <div class="bg-dark">
        <div class="container_custom">
            <div class="d-flex">
                <img src="../assets/img/logo-200x34.png" alt="logo azienda">
                <ul v-for="(element, index) in this.menu" :key="index">
                    <li class="light-grey"> {{element.voice[0] }} </li>
                    <li class="light-grey"> {{element.voice[1] }} </li>
                    <li class="light-grey"> {{element.voice[2] }} </li>
                    <li class="light-grey"> {{element.voice[3] }} </li>
                    <li class="light-grey"> {{element.voice[4] }} </li>
                    <ul v-for="element in menu" :key="element">
                        <li class="bg-yellow"> {{element.icons[0]}} </li>
                        <li><button>{{element.icons[1]}}</button></li>
                        <li><i class="fa-solid fa-cart-shopping"></i></li>
                        <li><i class="fa-solid fa-magnifying-glass"></i></li>
                    </ul>

                </ul>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'HeaderComp',
        components: {

        },
        data() {
            return {
                menu: [{
                        voice: [
                            'Home', 'Services', 'Videos', 'Blog', 'Store'
                        ],
                        icons: [
                            'new',
                            'Schedule a workout',

                        ]
                    },

                ],

            }
        }
    }
</script>

<style scoped lang="scss">
    .bg-dark {
        background-image:
            linear-gradient(to right,
                #060607 0px,
                #060607 80%,

            );
    }

    .container_custom {
        width: 80%;
        margin: 0 auto;
        padding: 10px 0;
    }

    .d-flex {
        display: flex;
        justify-content: space-between;
        align-items: center;
        text-align: center;
    }

    ul {
        color: white;
        display: flex;
        align-items: center;
        justify-content: space-between;
        list-style-type: none;

        li {
            padding: 5px;
            margin-left: 10px;
            color: grey;
            font-size: 1.2em;
        }
    }

    .bg-yellow {
        background-color: yellow;
        color: black;
        text-align: center;
        font-size: 0.8em;
        border-radius: 5px;
        padding: 10px;
        font-weight: bold;
    }

    .light-grey {
        color: lightgrey;
    }

    button {
        padding: 5px 10px;
        background-color: rgb(66, 66, 235);
        color: white;
        text-align: center;
        border-radius: 20px;
    }
    button:hover {
        background-color: #ff414b;
    }
</style>