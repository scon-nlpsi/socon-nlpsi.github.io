---
layout: page
permalink: /highlights/
title: Highlights
description: 
nav: true
nav_order: 4
---

<link rel="stylesheet" href="https://unpkg.com/flickity@2/dist/flickity.min.css">
<script src="https://unpkg.com/flickity@2/dist/flickity.pkgd.min.js"></script>


<h2>Photo Gallery</h2>

<div class="gallery js-flickity"
     data-flickity-options='{ "wrapAround": true, "autoPlay": 3000, "imagesLoaded": true }'>
  
  <div class="gallery-cell"><img src="/assets/img/highlights/keynote.jpeg" alt="Workshop Image 1"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/networking.jpeg" alt="Workshop Image 2"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/poster.jpeg" alt="Workshop Image 3"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/poster1.jpeg" alt="Workshop Image 4"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/poster2.jpeg" alt="Workshop Image 5"></div>

  <!-- Add more as needed -->
</div>

<style>
.gallery {
  background: #f8f8f8;
  margin-top: 1rem;
}

.gallery-cell {
  width: 70%;
  margin-right: 10px;
}

.gallery-cell img {
  display: block;
  width: 100%;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}
</style>
