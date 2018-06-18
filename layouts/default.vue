<template>
  <div>
    <div class="container">
      <nuxt-link to="/">
          <img src="~static/c1.png" alt="">
      </nuxt-link>
    </div>


    <div class="columns">
      <span>
        <nuxt-link to="/">
          <a class="button is-primary" style="width: 1000px">My self</a>
        </nuxt-link>
      </span>
      
      <span>
        <nuxt-link to="/story">
          <a class="button is-primary" style="width: 1000px">경력</a>
        </nuxt-link>
      </span>
    </div>
    <nuxt/>

  
  </div>


</template>

<style>
  .right {

    float: right;

  }
</style>