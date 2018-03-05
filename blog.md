---
layout: home2
permalink: /blog/
title: Contact Me
tagline: A List of Posts
tags: [blog]
comments: false
---
<div>
<img id = "signature" src = "{{ site.url }}/images/arda.png">
<style>
#signature {
  display: block;
  width: 90px;
  height: auto;
}
</style>
</div>

<br />

<div id="map"></div>
    <script>
      function initMap() {
        var uluru = {lat: -25.363, lng: 131.044};
        var map = new google.maps.Map(document.getElementById('map'), {
          zoom: 4,
          center: uluru
        });
        var marker = new google.maps.Marker({
          position: uluru,
          map: map
        });
      }
    </script>
    <script async defer
    src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCZ7nkwEKXfX_vWb1yhfhB0jQiN3tvKetQ&callback=initMap">
    </script>


<div class = "titled-image">
<figure class = "titled-image">
    <img src = "{{ site.url }}/images/arda.png">
    <figcaption>Lei Mao at Smoky Mountain in 2015</figcaption>
</figure>
</div>


