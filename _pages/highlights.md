---
layout: page
permalink: /highlights/
title: Highlights
description: 
nav: true
nav_order: 4
---

<!-- Flickity CSS & JS -->
<link rel="stylesheet" href="https://unpkg.com/flickity@2/dist/flickity.min.css">
<script src="https://unpkg.com/flickity@2/dist/flickity.pkgd.min.js"></script>

<h2>Snaps</h2>

<div class="gallery js-flickity"
     data-flickity-options='{ 
       "wrapAround": true, 
       "autoPlay": 3000, 
       "imagesLoaded": true, 
       "cellAlign": "left", 
       "contain": true 
     }'>

  <div class="gallery-cell"><img src="/assets/img/highlights/orga.jpeg" alt="Workshop Image 0"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/keynote.jpeg" alt="Workshop Image 1"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/networking.jpeg" alt="Workshop Image 2"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/poster.jpeg" alt="Workshop Image 3"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/poster2.jpeg" alt="Workshop Image 4"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/poster3.jpeg" alt="Workshop Image 5"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/audience.jpeg" alt="Workshop Image 6"></div>

</div>

<style>
.gallery {
  background: #f8f8f8;
  margin-top: 1rem;
}

/* Each cell can vary in width */
.gallery-cell {
  margin-right: 10px;
  flex: 0 0 auto;
  max-width: 90vw; /* Optional: prevent overflow */
}

/* Images scale to fit width; height adjusts automatically */
.gallery-cell img {
  display: block;
  width: 100%;
  height: auto;
  max-height: 80vh; /* Prevent super tall portraits from taking over */
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}
</style>
