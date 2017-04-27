---
permalink: /
layout: index
title: Homepage
show_call_to_action: false
show_chownow: true
---

<header class="homepage-cover cf-responsive">

  <div class="homepage-cover__overlay">
  </div>

  <div class="homepage-cover__content">
    <img class="homepage-cover__content__crest" src="/assets/img/logo--monogram--gold.svg">
    <img class="homepage-cover__content__masthead" src="/assets/img/logo--masthead.svg">
    <span class="homepage-cover__content__tagline editable">Updated website coming soon!</span>

    <div class="homepage-cover__content__icons">
      <a href="tel:{{site.data.settings.location.phone_number}}">
        <img src="/assets/img/call.svg">
        <span>Call</span>
      </a>
      <a href="/menu/eats">
        <img src="/assets/img/menu.svg">
        <span>Menu</span>
      </a>
      <a href="/location">
        <img src="/assets/img/directions.svg">
        <span>Map</span>
      </a>
    </div>

  </div>


  <div class="homepage-cover__foot">
    <div class="homepage-cover__foot__container">

      <a class="homepage-cover__foot__hours" id="open-hours-modal">
        <span id="open-today">Open Today:</span>
        <span>Show All Hours</span>
      </a>

      <div class="homepage-cover__foot__social">
        <a href="{{site.data.settings.social_media.yelp_url}}" target="_blank"><img src="/assets/img/social-yelp--light.svg"></a>
        <a href="{{site.data.settings.social_media.instagram_url}}" target="_blank"><img src="/assets/img/social-instagram--light.svg"></a>
        <a href="{{site.data.settings.social_media.twitter_url}}" target="_blank"><img src="/assets/img/social-twitter--light.svg"></a>
        <a href="{{site.data.settings.social_media.facebook_url}}" target="_blank"><img src="/assets/img/social-facebook--light.svg"></a>
      </div>

    </div>
  </div>

</header>
