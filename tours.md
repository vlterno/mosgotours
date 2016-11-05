---
layout: home
title: Tours
permalink: /tours/
---

<div class="head-block">
  <div class="title-h-b">
    <h1>Free Walking Tours</h1>
    <p class="mini-title-t-h-b">From locals with love</p>
  </div>
</div>

<div class="container marketing">
  
  <div class="row">
  {% for post in site.posts %}
    <div class="col-md-4 col-lg-4">
      <img class="img-circle" src="{{ post.icon }}" alt="Generic placeholder image" width="140" height="140">
      <h2>{{ post.title }}</h2>
      <p>{{ post.description_tour }}</p>
      <p><a class="btn btn-default" href="{{ post.url }}" role="button" {{ post.status }}>Let's go! &raquo;</a></p>
    </div>
  {% endfor %}
  </div>