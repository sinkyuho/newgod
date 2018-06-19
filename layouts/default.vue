<template>
  <div>
    <div class="container">
      <nuxt-link to="/">
          <img src="~static/c1.png" alt="">
      </nuxt-link>
    </div>


    <div class="container" style="text-align: center">
      <span>
        <nuxt-link to="/">
          <a class="button is-primary" style="width: 650px">My self</a>
        </nuxt-link>
      </span>
      
      <span>
        <nuxt-link to="/story">
          <a class="button is-primary" style="width: 650px">경력</a>
        </nuxt-link>
      </span>
    </div>
    <nuxt/>

    
    <br>
  
  </div>

</template>

<style>
  .right {

    float: right;

  }

</style>