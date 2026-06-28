---
title: Gallery
parent: News &<br>Events
nav:
    order: 3
permalink: /gallery/
---

# Gallery

/* Styling for the Main Outer Frame (the Box) */
.image-gallery-frame {
  border: 3px solid #666; /* The main frame/box border */
  border-radius: 12px; /* Rounds the corners */
  padding: 25px;
  max-width: 900px; /* Constrains the width */
  margin: 30px auto; /* Centers the whole gallery on the page */
  background-color: #f9f9f9; /* Box background */
  box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* Adds depth */
}

/* Styling for the Title within the Frame */
.gallery-title {
  text-align: center;
  margin-top: 0;
  margin-bottom: 25px;
  font-family: 'Helvetica Neue', Helvetica, sans-serif;
  color: #333;
  font-size: 1.8em;
  padding-bottom: 10px;
  border-bottom: 2px solid #ddd; /* A subtle line under the title */
}

/* Styling to Create the Grid Layout for the Images */
.image-grid {
  display: grid; /* Uses modern CSS Grid layout */
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); /* Automatically adds columns */
  gap: 20px; /* Space between grid items */
  list-style-type: none; /* Removes bullet points */
  padding: 0;
  margin: 0;
}

/* Styling for Individual Image Containers */
.image-grid li {
  background-color: white;
  border: 1px solid #eee;
  border-radius: 8px;
  padding: 10px;
  text-align: center;
}

/* Styling to make the Images behave correctly */
.image-grid img {
  max-width: 100%; /* Prevents images from overflowing */
  height: auto; /* Maintains aspect ratio */
  display: block; /* Removes baseline spacing issues */
  margin: 0 auto;
}

/* Styling for the Small Caption underneath each Image */
.caption {
  margin: 10px 0 0 0;
  font-size: 0.9em;
  color: #555;
  font-style: italic;
}

<!-- 
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
</style> -->

## SPR 2026

<div class="image-gallery-frame">
  <h3 class="gallery-title">Strcuctured Discussion titled: Using Research to lmprove Training and Care: Implementing ROM and Research in Training Clinics</h3>
  
  <ul class="image-grid">
    <li>
      <img src="news_events_gallery/spr2026_images/ROMdiscussion1.jpg" alt="">
      <p class="caption">Discussants</p>
    </li>
    <li>
      <img src="news_events_gallery/spr2026_images/ROMdiscussion2.jpg" alt="">
      <p class="caption">need to add name</p>
    </li>
    <li>
      <img src="news_events_gallery/spr2026_images/ROMdiscussion3.jpg" alt="">
      <p class="caption">need to add name</p>
    </li>
    </ul>
</div>

<div class="gallery-box" style="display: flex; flex-wrap: wrap; gap: 30px; justify-content: center; width: 100%; text-align: left;">

  {% include gallery-multi-picture.html 
    title="Strcuctured Discussion titled: Using Research to lmprove Training and Care: Implementing ROM and Research in Training Clinics" 
    images="news_events_gallery/spr2026_images/ROMdiscussion1.jpg, news_events_gallery/spr2026_images/ROMdiscussion2.jpg, news_events_gallery/spr2026_images/ROMdiscussion3.jpg, news_events_gallery/spr2026_images/ROMdiscussion4.jpg" 
  %}

  {% include gallery-multi-picture.html 
    title="Panel titled: Revolutionizing Psychotherapy and Trainingwith Al: Insights from Virtual Human Interactions, NLP, and AI acceptability Studies" 
    images="news_events_gallery/spr2026_images/panel2.jpg, news_events_gallery/spr2026_images/panel3.jpg, news_events_gallery/spr2026_images/panel4.jpg, news_events_gallery/spr2026_images/panel1.jpg"   
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
      title="<div style='text-align: center;'>R01 Grant Submission Celebration Party 2026 June 17th</div>" 
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
    images="news_events_gallery/gallery_images/2025 Lausanne Conference 3.jpg, news_events_gallery/gallery_images/2025 Lausanne Conference 1.jpg, news_events_gallery/gallery_images/2025 Lausanne Conference 2.jpg, news_events_gallery/gallery_images/2025 Lausanne Conference 4.jpg" 
  %}

  {% include gallery-multi-picture.html 
    title="IASR/AFSP Summit 2025" 
    images="news_events_gallery/new_images/IASR3.jpeg,news_events_gallery/new_images/IASR2.jpeg,news_events_gallery/new_images/IASR7.jpg, news_events_gallery/new_images/IASR6 with shira.jpg, news_events_gallery/new_images/IASR5.jpeg,news_events_gallery/new_images/IASR4.jpeg,news_events_gallery/new_images/IASR1.jpeg, news_events_gallery/new_images/IASR8.jpg,news_events_gallery/new_images/IASR9.jpg" 
  %}
</div>
