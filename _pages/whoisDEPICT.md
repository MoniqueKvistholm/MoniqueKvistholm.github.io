---
layout: page2
permalink: /whoisDEPICT/
title: Who is DEPICT
nav: false
nav_order: 
---

<style>
  .hero-section {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 600px; /* Øget højden af hero-sektionen */
    background-color: #9DC0D1;
    overflow: hidden;
    position: relative;
  }
  .hero-image {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    z-index: -1;
  }
  .hero-content {
    max-width: 50%;
    padding: 20px;
    background-color: rgba(255, 255, 255, 0.9); /* Transparent hvid baggrund */
    text-align: center;
    color: #004062;
    font-size: 1.2em; /* Mindre tekststørrelse */
    line-height: 1.5; /* Mindre linjeafstand */
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1); /* Skyggeeffekt */
    position: relative;
    z-index: 1;
  }
  .hero-content h1 {
    font-size: 3em;
    margin-bottom: 20px;
  }
  .section {
    width: 100vw;
    margin-left: calc(50% - 50vw);
    padding: 40px 0;
  }
  .content {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }
  .section-title {
    color: #004062;
    font-size: 2em;
    margin-bottom: 20px;
  }
  .vision-list {
    list-style-type: none;
    padding: 0;
  }
  .vision-item {
    background-color: #f2f2f2;
    border-radius: 5px;
    margin-bottom: 10px;
    padding: 20px;
  }
</style>

<!-- Hero Section with Large Image and Text Overlay -->
<div class="hero-section">
  <img src="/assets/img/Design1.jpg" alt="Illustrationsbillede" class="hero-image">
  <div class="hero-content">
    <h1>Om DEPICT</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus lacinia odio vitae vestibulum vestibulum. Cras venenatis euismod malesuada. Nullam ac erat ante. Ut quis quam vel arcu lacinia feugiat id et nisl.</p>
    <p>Nullam tincidunt arcu non eros eleifend, sit amet fermentum felis facilisis. Integer hendrerit vel risus vel eleifend. Mauris venenatis, odio id accumsan tincidunt, eros ligula hendrerit urna, non ultricies nisi ex id ipsum.</p>
    <p>Curabitur sollicitudin fermentum justo nec vestibulum. Suspendisse potenti. Nullam nec sapien nec ipsum malesuada consequat. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>
  </div>
</div>

<!-- About Us Section -->
<div class="section" style="background-color: #f9f9f9;">
  <div class="content">
    <h2 class="section-title">Who We Are</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus lacinia odio vitae vestibulum vestibulum. Cras venenatis euismod malesuada. Nullam ac erat ante.</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus lacinia odio vitae vestibulum vestibulum. Cras venenatis euismod malesuada. Nullam ac erat ante.</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus lacinia odio vitae vestibulum vestibulum. Cras venenatis euismod malesuada. Nullam ac erat ante.</p>
  </div>
</div>

<!-- Vision Section -->
<div class="section" style="background-color: #d0d0d0;">
  <div class="content">
    <h2 class="section-title">Our Vision</h2>
    <ul class="vision-list">
      <li class="vision-item">Vision 1: Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
      <li class="vision-item">Vision 2: Vivamus lacinia odio vitae vestibulum vestibulum.</li>
      <li class="vision-item">Vision 3: Cras venenatis euismod malesuada.</li>
    </ul>
  </div>
</div>

<!-- Additional Sections -->
<div class="section" style="background-color: #c0c0c0;">
  <div class="content">
    <h2 class="section-title">Additional Information</h2>
    <p>Additional content can be added here, such as more information about your organization, testimonials, case studies, etc.</p>
  </div>
</div>
