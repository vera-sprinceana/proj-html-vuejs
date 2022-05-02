<template>
  <div class="bg-dark py-5 text-white text-center">
    <div class="container py-5 d-flex justify-content-center align-self-center text-center text-white">
      <!-- SPONSOR YOGA -->
      <div class=" col-4 ">
        <img src="../assets/img/logo-200x34.png" alt="">
        <p>
          Ac aliquam neque sagittis diam faucibus vitae purus turpis phasellus. Pellentesque consectetur amet purus
          ultrices mauris.
        </p>
        <ul class="col-right">
          <li>
            <img src="../assets/img/icons8-f-di-facebook-50.png" alt="">
          </li>
          <li>
            <img src="../assets/img/icons8-twitter-50.png" alt="">
          </li>
          <li>
            <img src="../assets/img/icons8-riproduci-youtube-50.png" alt="">
          </li>
          <li>
            <img src="../assets/img/icons8-instagram-50.png" alt="">
          </li>
          <li>
            <img src="../assets/img/icons8-linkedin-2-50.png" alt="">
          </li>
        </ul>
      </div>
      <!-- SPONSOR FITNESS CENTER -->
      <div class=" col-4">
        <ul>
          <li>
            <h5 class="text-uppercase">recent posts</h5>
          </li>
          <li><i class="fa-solid fa-angle-right"></i> The best protein shake</li>
          <li><i class="fa-solid fa-angle-right"></i> Ultimate cardio workout</li>
          <li><i class="fa-solid fa-angle-right"></i> New juices available now</li>
          <li><i class="fa-solid fa-angle-right"></i> Tips to find training partners</li>
          <li><i class="fa-solid fa-angle-right"></i> 20 best healthy recipes</li>
        </ul>
      </div>
      <!-- SPONSOR FITNESS CLUB -->
      <div class="col-4">
        <ul>
          <li>
            <h5 class="text-uppercase ">contact informations</h5>
          </li>
          <li>4746 Tipple Road Michigan 48449</li>
          <li>
            <h6>Mobile: 1.800.000.0000</h6>
          </li>
          <li>
            <h6>Email: info@your-company.com</h6>
          </li>
        </ul>
      </div>
    </div>
    <hr>
    <div class="grey"><i class="fa-regular fa-copyright"></i>
    Copyright 2012 - 2020 | Avada theme by <span class="text-white">ThemeFusion</span> | All rights reserved | Powered by <span class="text-white">WordPress</span>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'FooterComp',
    components: {

    }
  }
</script>

<style scoped lang="scss">
  
  .col-right {
    list-style-type: none;
    display: flex;
    justify-content: center;

    img {
      width: 25px;
      margin: 5px;
    }

  }

  ul {
    list-style-type: none;

    li {
      padding: 5px 0
    }
  }

  p {
    padding: 10px 35px;
    margin: 10px 0;
  }
  .grey{
    color: grey;
  }
</style>