---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

<div class="head-block">
  <div class="title-h-b">
    <h1>Lomonosov MSU <br> Free Walking Tour</h1>
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
<!--     <div class="col-md-4 col-lg-4">
      <img class="img-circle" src="{{ "images/moscow_metro.jpg" | absolute_url }}" alt="Generic placeholder image" width="140" height="140">
      <h2>Moscow Metro tour</h2>
      <p>Moscow Metro is a rapid transit system serving Moscow, Russia and the neighbouring Moscow Oblast towns of Krasnogorsk, Reutov, Lyubertsy and Kotelniki. Opened in 1935. As of 2016, the Moscow Metro has 203 stations.</p>
      <p><a class="btn btn-default" href="#" role="button" disabled>Coming soon!</a></p>
    </div> -->
<!--     <div class="col-md-4 col-lg-4">
      <img class="img-circle" src="{{ "images/moscow_city.jpg" | absolute_url }}" alt="Generic placeholder image" width="140" height="140">
      <h2>Moscow City tour</h2>
      <p>Moscow International Business Center “Moscow City” is a commercial district. MIBC includes 6 skyscrapers with maximum height of 300 meters or more. Europe's tallest building, the Federation Tower, is in the Moscow IBC.</p>
      <p><a class="btn btn-default" href="#" role="button" disabled>Coming soon!</a></p>
    </div> -->
    {% endfor %}
  </div>
  

<!--   <div class="row">
    <div class="col-md-4 col-lg-4">
    <img class="img-circle" src="{{ "images/lomonosov_msu.jpg" | absolute_url }}" alt="Generic placeholder image" width="140" height="140">
      <h2>Lomonosov Moscow State University <br> (free tour)</h2>
      <p>The tour covers all the must-see sites, stories & legends of the university and ends at the viewing platform on Sparrow Hills.</p>
      <p><a class="btn btn-default" href="#" role="button">Let's go! &raquo;</a></p>
    </div>
    <div class="col-md-4 col-lg-4">
      <img class="img-circle" src="{{ "images/moscow_metro.jpg" | absolute_url }}" alt="Generic placeholder image" width="140" height="140">
      <h2>Moscow Metro tour</h2>
      <p>Moscow Metro is a rapid transit system serving Moscow, Russia and the neighbouring Moscow Oblast towns of Krasnogorsk, Reutov, Lyubertsy and Kotelniki. Opened in 1935. As of 2016, the Moscow Metro has 203 stations.</p>
      <p><a class="btn btn-default" href="#" role="button" disabled>Coming soon!</a></p>
    </div>
    <div class="col-md-4 col-lg-4">
      <img class="img-circle" src="{{ "images/moscow_city.jpg" | absolute_url }}" alt="Generic placeholder image" width="140" height="140">
      <h2>Moscow City tour</h2>
      <p>Moscow International Business Center “Moscow City” is a commercial district. MIBC includes 6 skyscrapers with maximum height of 300 meters or more. Europe's tallest building, the Federation Tower, is in the Moscow IBC.</p>
      <p><a class="btn btn-default" href="#" role="button" disabled>Coming soon!</a></p>
    </div>
  </div> -->

  <hr class="featurette-divider">

  <div class="row featurette">
    <div class="col-md-7">
      <h2 class="featurette-heading">Showing you Lomonosov MSU and loving it</h2>
      <p class="lead">We love our university and we love sharing it with fun-lovin' curious travelers, so you can really get to understand the remarkable and unique wonderland that is Lomonosov MSU.</p>
    </div>
    <div class="col-md-5">
      <img class="featurette-image img-responsive center-block" src="{{ "images/moscow_state_university.jpg" | absolute_url }}" alt="Generic placeholder image">
    </div>
  </div>

  <hr class="featurette-divider">

  <div class="row featurette">
    <div class="col-md-7 col-md-push-5">
      <h2 class="featurette-heading">Oh yeah, it's that good</h2>
      <p class="lead">Our fantastic student guides take you through the history of the main university of Russia on fun-filled, enjoyable and free walking tours of the highest standard. These young, professional, local freelance guides provide these exceptional tours for tips only, making top-quality, authentic experiences available to all travelers regardless of budget. Get more from your Moscow adventure with us</p>
    </div>
    <div class="col-md-5 col-md-pull-7">
      <iframe name="f3617b77326bae4" width="280px" height="130px" frameborder="0" allowtransparency="true" allowfullscreen="true" scrolling="no" title="fb:page Facebook Social Plugin" src="https://www.facebook.com/v2.4/plugins/page.php?adapt_container_width=true&amp;app_id=304553036307597&amp;channel=http%3A%2F%2Fstaticxx.facebook.com%2Fconnect%2Fxd_arbiter%2Fr%2FfTmIQU3LxvB.js%3Fversion%3D42%23cb%3Dff89878f050b%26domain%3Dwww.mosgotours.com%26origin%3Dhttp%253A%252F%252Fwww.mosgotours.com%252Ffa75a4b67869f%26relation%3Dparent.parent&amp;container_width=280&amp;height=130&amp;hide_cover=false&amp;href=http%3A%2F%2Fwww.facebook.com%2F341601146183989&amp;locale=en_US&amp;sdk=joey&amp;show_facepile=false&amp;show_posts=false&amp;width=280" style="border: none; visibility: visible; width: 280px; height: 130px;" class=""></iframe>
      <iframe class="advisor" width="100%" height="100%" src="http://www.mosgotours.com.usrfiles.com/html/3854c7_20dac9b932d3900f4c2c07d1cd592305.html" data-reactid=".0.$SITE_ROOT.$desktop_siteRoot.$PAGES_CONTAINER.1.1.$SITE_PAGES.$cjg9.1.$comp-iu3ywmlz.0.0"></iframe>
    </div>
  </div>
</div>