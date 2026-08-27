---
layout: page
title: gallery
permalink: /gallery/
description: moments from the HiACE Lab
nav: true
nav_order: 6
---

<div class="hiace-gallery">

  <div class="gallery-item">
    {% include figure.liquid
      path="assets/img/gallery/hfes_2025.jpg"
      class="img-fluid rounded z-depth-1"
      zoomable=true
      alt="HiACE Lab at HFES 2025"
      caption="HiACE Lab presenting our research at HFES 2025."
    %}
  </div>

  <div class="gallery-item">
    {% include figure.liquid
      path="assets/img/gallery/trb_2026.jpg"
      class="img-fluid rounded z-depth-1"
      zoomable=true
      alt="HiACE Lab at TRB 2026"
      caption="HiACE Lab members at the Transportation Research Board Annual Meeting 2026."
    %}
  </div>

  <div class="gallery-item">
    {% include figure.liquid
      path="assets/img/gallery/lab_meeting_2026.jpg"
      class="img-fluid rounded z-depth-1"
      zoomable=true
      alt="HiACE Lab research meeting"
      caption="A research meeting at the HiACE Lab, Texas Tech University."
    %}
  </div>

  <div class="gallery-item">
    {% include figure.liquid
      path="assets/img/gallery/group_photo_2026.jpg"
      class="img-fluid rounded z-depth-1"
      zoomable=true
      alt="HiACE Lab group photo"
      caption="HiACE Lab group photo, Texas Tech University."
    %}
  </div>

</div>

<style>
.hiace-gallery {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 28px 22px;
  margin-top: 1.5rem;
}

.gallery-item {
  min-width: 0;
}

.gallery-item figure {
  margin: 0;
}

.gallery-item img {
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
}

.gallery-item .caption {
  margin-top: 8px;
  font-size: 0.9rem;
  line-height: 1.4;
  text-align: center;
}

@media (max-width: 768px) {
  .hiace-gallery {
    grid-template-columns: 1fr;
  }
}
</style>
