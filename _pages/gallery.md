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
      path="assets/img/gallery/cvpr_2026.jpg"
      class="img-fluid rounded z-depth-1"
      zoomable=true
      alt="ICR-Drive poster presentation at CVPR 2026"
      caption="Presenting ICR-Drive at the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2026) in Denver, Colorado."
    %}
  </div>

  <div class="gallery-item">
    {% include figure.liquid
      path="assets/img/gallery/lab_lunch_spring26.jpg"
      class="img-fluid rounded z-depth-1"
      zoomable=true
      alt="HiACE Lab lunch in Spring 2026"
      caption="HiACE Lab lunch, Spring 2026."
    %}
  </div>

  <div class="gallery-item">
    {% include figure.liquid
      path="assets/img/gallery/research_day_kaiser.jpg"
      class="img-fluid rounded z-depth-1"
      zoomable=true
      alt="FSDAM poster presentation at Texas Tech University Research Day"
      caption="Presenting FSDAM: Few-Shot Driver Attention Modeling via Vision-Language Coupling at Texas Tech University Research Day."
    %}
  </div>

  <div class="gallery-item">
    {% include figure.liquid
      path="assets/img/gallery/research_day_li.jpg"
      class="img-fluid rounded z-depth-1"
      zoomable=true
      alt="Risk perception research poster at Texas Tech University Research Day"
      caption="Presenting research on driver risk perception and traffic-density transitions at Texas Tech University Research Day."
    %}
  </div>

  <div class="gallery-item">
    {% include figure.liquid
      path="assets/img/gallery/training_av_sim.jpg"
      class="img-fluid rounded z-depth-1"
      zoomable=true
      alt="Autonomous driving simulator training in the HiACE Lab"
      caption="Hands-on training with the autonomous driving simulator in the HiACE Lab."
    %}
  </div>

  <div class="gallery-item">
    {% include figure.liquid
      path="assets/img/gallery/trb_2026.JPG"
      class="img-fluid rounded z-depth-1"
      zoomable=true
      alt="HiACE Lab at TRB 2026"
      caption="HiACE Lab members at the Transportation Research Board Annual Meeting 2026."
    %}
  </div>

</div>

<style>

.hiace-gallery {
  column-count: 2;
  column-gap: 24px;
  margin-top: 1.5rem;
}

.gallery-item {
  display: inline-block;
  width: 100%;
  margin: 0 0 28px;
  break-inside: avoid;
  -webkit-column-break-inside: avoid;
  page-break-inside: avoid;
}

.gallery-item figure {
  margin: 0;
}

.gallery-item img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 6px;
}

.gallery-item .caption {
  margin-top: 8px;
  padding: 0 4px;
  font-size: 0.9rem;
  line-height: 1.4;
  text-align: center;
}

@media (max-width: 768px) {
  .hiace-gallery {
    column-count: 1;
  }
}

</style>
