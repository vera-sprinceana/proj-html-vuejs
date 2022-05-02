<template>
  <div class="bg-dark py-5 text-white text-center">
    <div class="container py-5 d-flex justify-content-center align-self-center text-center text-white">
     
      <div class=" col-4" v-for="(element, index) in immagini" :key="index">
        <img src="../assets/img/logo-200x34.png" alt="">
        <p> {{element.paragraph}} </p>
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
     
      <div class=" col-4">
        <h5 class="text-uppercase ms-4">recent posts</h5>
        <ul  v-for="(element, index) in posts" :key="index">
          <li><i class="fa-solid fa-angle-right"></i>{{element.post}}</li>
          <!-- <li><i class="fa-solid fa-angle-right"></i> Ultimate cardio workout</li>
          <li><i class="fa-solid fa-angle-right"></i> New juices available now</li>
          <li><i class="fa-solid fa-angle-right"></i> Tips to find training partners</li>
          <li><i class="fa-solid fa-angle-right"></i> 20 best healthy recipes</li> -->
        </ul>
      </div>
      <!-- SPONSOR FITNESS CLUB -->
      <div class="col-4 text-center">
        <h5 class="text-uppercase ms-4">contact informations</h5>
        <ul v-for="(element, index) in contact" :key="index" class="">
          <li>{{element.adress}} </li>
          <li>
            <h6>{{element.phone}} </h6>
          </li>
          <li>
            <h6>{{element.email}} </h6>
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
    data(){
      return {
        immagini:[
          { 
            paragraph:' Ac aliquam neque sagittis diam faucibus vitae purus turpis phasellus. Pellentesque consectetur amet purus ultrices mauris.'
          }
        ],
        socialMedia:[
          {
            id:0,
            media:'../assets/img/icons8-f-di-facebook-50.png'
          },
           {
            id:1,
            media:'../assets/img/icons8-twitter-50.png'
          },
           {
            id:2,
            media:'../assets//img/icons8-riproduci-youtube-50.png'
          },
           {
            id:3,
            media:'../assets/img/icons8-instagram-50.png'
          },
           {
            id:4,
            media:'../assets/img/icons8-linkedin-2-50.png'
          },
        ],
        posts: [
          {
            id: 0,
            title:'recent posts'
          },
          {
            id:1,
            post: 'The best protein shake'
          },
          {
            id:2,
            post: 'Ultimate cardio workout'
          },
          {
            id:3,
            post: 'New juices available now'
          },
          {
            id:4,
            post: 'Tips to find training partners'
          },
          {
            id:5,
            post: '20 best healthy recipes'
          },
        ],
        contact: [
          {
            adress: '4746 Tipple Road Michigan 48449'
          },
          {
            phone:'Mobile: 1.800.000.0000'
          },
          {
            email:'Email: info@your-company.com'
          }
        ]
      }
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