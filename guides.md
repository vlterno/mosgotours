---
layout: home
title: Guides
permalink: /guides/
---

<style type="text/css">
  .head-block {
    height: 500px;
    margin-bottom: 60px;
    background-image: url(../images/bg_guides.jpg);
    background-position: center;
    background-size: cover;
    display: flex;
    justify-content: center;
    color: #ffffff;
    font-size: 5rem;
    text-align: center;
}  
</style>

<div class="head-block">
  <div class="title-h-b">
    <h1>Our guides</h1>
    <p class="mini-title-t-h-b">From locals with love</p>
  </div>
</div>

<div class="container marketing guides">
  
  {% for guide in site.guides %}
  <div class="row">
    <div class="col-md-4 col-lg-4 guide-logo">
      <img class="img-circle" src="{{ guide.avatar }}" alt="Generic placeholder image" width="140" height="140">
    </div>
    <div class="col-md-8 col-lg-8">
      <h2>{{ guide.name }}</h2>
      <p>{{ guide.description }}</p>
      <h4>Languges:</h4>
      <p>{{ guide.languages }}</p>
      <h4>Tour:</h4>
      <p>{{ guide.tour }}</p>
   </div>
  </div>
  {% endfor %}

</div>