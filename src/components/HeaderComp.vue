<template>
  <div class="bg-dark">
      <div class="container">
          <div class="d-flex">
              <img src="../assets/img/logo-200x34.png" alt="logo azienda">
              <ul>
                  <li class="light-grey">Home</li>
                  <li>Services</li>
                  <li>About</li>
                  <li>Videos</li>
                  <li>Blog</li>
                  <li>Store</li>
                  <li class="bg-yellow">new</li>
                  <li><button>Schedule a workout</button></li>
                  <li><i class="fa-solid fa-cart-shopping"></i></li>
                  <li><i class="fa-solid fa-magnifying-glass"></i></li>
              </ul>
          </div>
      </div>
  </div>
</template>

<script>


export default {
  name: 'HeaderComp',
  components: {
  
  }
}
</script>

<style scoped lang="scss">
    .bg-dark{
        background-color: black;
    }
    .container{
        width: 80%;
        margin: 0 auto;
        padding: 20px 0;
    }
    .d-flex{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    ul{
        color: white;
        display: flex;
        align-items: center;
        justify-content: space-between;
        list-style-type: none;
        li{
            padding: 5px;
            margin-left: 10px;
            color: grey;
            font-size: 1.2em;
        }
    }
    .bg-yellow{
        background-color: yellow;
        color: black;
        text-align: center;
        font-size: 0.8em;
        border-radius: 5px;
        padding: 10px;
        font-weight: bold;
    }
    .light-grey{
        color: lightgrey;
    }
    button{
        padding: 10px 15px;
        background-color: rgb(66, 66, 235);
        color: white;
        text-align: center;
        border-radius: 20px;
    }
</style>