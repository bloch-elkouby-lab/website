---
title: Gallery
parent: News &<br>Events
nav:
    order: 3
permalink: /gallery/
---

# Gallery

<style>
  /* This catches titles in the multi-galleries AND captions in the single galleries */
  .gallery-box h3, 
  .gallery-box h4, 
  .gallery-box h5, 
  .gallery-box p, 
  .gallery-box figcaption, /* Added for standard HTML captions */
  .gallery-box span,
  .gallery-box div {
    font-size: 20px !important;  
    color: #000000 !important;   
    font-weight: 600 !important; 

  /* FIXES FOR SPACING: */
    letter-spacing: -0.2px !important; /* Tightens the space between individual letters */
    line-height: 1.2 !important;       /* Pulls lines closer together if the title wraps to a second line */
    margin-bottom: 6px !important;     /* Reduces the gap between the title and the images underneath */
    margin-top: 0px !important;        /* Prevents the theme from pushing the title down too far */
  }
</style>

## SPR 2026
<div class="gallery-box" style="display: flex; flex-wrap: wrap; gap: 30px; justify-content: center; width: 100%; text-align: left;">

  {% include gallery-multi-picture.html 
    title="Strcuctured Discussion titled: Using Research to lmprove Training and Care: Implementing ROM and Research in Training Clinics" 
    images="news_events_gallery/spr2026_images/discussion1.jpg, news_events_gallery/spr2026_images/discussion2.jpg" 
  %}

  {% include gallery-multi-picture.html 
    title="Panel titled: Revolutionizing Psychotherapy and Trainingwith Al: Insights from Virtual Human Interactions, NLP, and AI acceptability Studies" 
    images="news_events_gallery/spr2026_images/bloch-talk-1.jpg, news_events_gallery/spr2026_images/blocktalk2.jpg, news_events_gallery/spr2026_images/talk3.jpg"   
  %}

  {% include gallery-multi-picture.html 
    title="In person poster by Jimmy Chen" 
    images="news_events_gallery/spr2026_images/jimmyposter2.jpg, news_events_gallery/spr2026_images/jimmyposter1.jpg, news_events_gallery/spr2026_images/jimmyposter3.jpg"   
  %}

  {% include gallery-multi-picture.html 
    title="Outstanding Early Career Achievement Award" 
    images="news_events_gallery/spr2026_images/award1.jpg, news_events_gallery/spr2026_images/award2.jpg, news_events_gallery/spr2026_images/award3.jpg, news_events_gallery/spr2026_images/award4.jpg"   
  %}
</div>


## Lab Outings
<div class="gallery-box" style="max-width: 80%; margin: 0 auto;">
  {% include gallery-multi-picture.html 
      title="<div style='text-align: center;'>R01 Grant Submission Celebration Party</div>" 
      images="news_events_gallery/gallery_images/R01_party1.PNG, news_events_gallery/gallery_images/R01_party2.jpg" 
  %}
</div>

<div class="gallery-box" style="display: flex; flex-wrap: wrap; gap: 30px; justify-content: center; width: 100%; text-align: left;">

  {% include gallery-picture.html
  image="news_events_gallery/gallery_images/2026.01.27-Milktea.jpg"
  caption="Milktea 2026"
  %}

  {% include gallery-picture.html
  image="news_events_gallery/gallery_images/2026.01.06-Hotpot.jpg"
  caption="Hotpot 2026"
  %}
</div>


## Past Events
<div class="gallery-box" style="display: flex; flex-wrap: wrap; gap: 30px; justify-content: center; width: 100%; text-align: left;">

  {% include gallery-multi-picture.html 
    title="Conference on suicide at the University of Lausanne, November 2025" 
    images="news_events_gallery/gallery_images/2025 Lausanne Conference 3.jpg, news_events_gallery/gallery_images/2025 Lausanne Conference.jpg, news_events_gallery/gallery_images/2025 Lausanne Conference2.jpg, news_events_gallery/gallery_images/2025 Lausanne Conference 4.jpg" 
  %}

  {% include gallery-multi-picture.html 
    title="IASR/AFSP Summit 2025" 
    images="news_events_gallery/new_images/IASR3.jpeg,news_events_gallery/new_images/IASR2.jpeg,news_events_gallery/new_images/IASR7.jpg, news_events_gallery/new_images/IASR6 with shira.jpg, news_events_gallery/new_images/IASR5.jpeg,news_events_gallery/new_images/IASR4.jpeg,news_events_gallery/new_images/IASR1.jpeg, news_events_gallery/new_images/IASR8.jpg,news_events_gallery/new_images/IASR9.jpg" 
  %}
</div>
