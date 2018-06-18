<template>
    <div>
        <div class="container">
          <nuxt-link to="/" >
              <figure class="image is-128x128">
                <img src="~static/c1.png" alt="">
            </figure>
          </nuxt-link>
        </div>
      <nuxt/>

      <nav class="navbar">
       <div class="columns">
            <span> <nuxt-link to="/" > <a class="button is-primary"  style="width: 800px">My self</a> </nuxt-link> </span> 
            <span> <nuxt-link to="/story" > <a class="button is-primary"  style="width: 800px">경력</a> </nuxt-link> </span>
       </div>
      </nav>

      <footer class="footer has-text-centered">
        <div>
        <figure class="image is-32x32">
        </figure>2018년 목원대학교 개사랑. 모든 저작권은 개사랑에 있습니다.</div>
      </footer>
    </div>
  </template>

  <style>
      .right {
      
        float: right;
      
      }
    </style>