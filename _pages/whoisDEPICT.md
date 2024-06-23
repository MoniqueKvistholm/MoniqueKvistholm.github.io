---
layout: page2
permalink: /whoisDEPICT/
title: Who is DEPICT
nav: false
nav_order: 
---

<style>
  body {
    margin: 0; /* Fjern standard margener */
  }
  .hero-section {
    display: flex;
    min-height: 100vh; /* Brug min-height for at tillade sektionen at vokse */
    background-color: #9DC0D1;
  }
  .hero-image-container {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden; /* Skjuler overskydende indhold */
  }
  .hero-image {
    max-width: 100%;
    max-height: 100%;
    object-fit: contain; /* Vis hele billedet uden at beskære det */
  }
  .hero-content {
    flex: 1;
    padding: 40px 20px; /* Juster padding for at øge højden på boksen */
    text-align: center; /* Centrer tekst */
    color: #004062;
    background-color: #F0F0F; /* Knækket hvid baggrundsfarve */
    border-radius: 10px; /* Afrundede kanter */
    display: flex;
    flex-direction: column;
    justify-content: center; /* Centrer indholdet vertikalt */
  }
  .hero-content h1 {
    font-size: 2.5em; /* Mindre font-størrelse */
    font-weight: bold; /* Federe tekst */
    margin-bottom: 20px;
    color: #1F4A60; /* Overskriftens farve */
  }
  .hero-content p {
    font-size: 1.2em;
    line-height: 1.5;
  }
  .section {
    width: 100vw; /* Fyld viewportens bredde */
    padding: 40px 20px; /* Juster padding efter behov */
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .content {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    text-align: center; /* Centrer teksten */
    background-color: #F0F0F0; /* Knækket hvid baggrundsfarve */
    border-radius: 10px; /* Afrundede kanter */
    color: #004062;
  }
  .section-title {
    color: #1F4A60; /* Overskriftens farve */
    font-size: 2.2em; /* Større font-størrelse */
    font-weight: bold; /* Federe tekst */
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
    font-size: 1.2em; /* Øg font-størrelsen */
    font-weight: bold; /* Gør teksten fed */
    line-height: 1.6;
  }
</style>

<!-- Hero Section with Large Image and Text Overlay -->
<div class="hero-section">
  <div class="hero-image-container">
    <img src="/assets/img/Design4.jpg" alt="Illustrationsbillede" class="hero-image">
  </div>
  <div class="hero-content">
    <h1>About DEPICT</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus lacinia odio vitae vestibulum vestibulum. Cras venenatis euismod malesuada. Nullam ac erat ante. Ut quis quam vel arcu lacinia feugiat id et nisl.</p>
    <p>Nullam tincidunt arcu non eros eleifend, sit amet fermentum felis facilisis. Integer hendrerit vel risus vel eleifend. Mauris venenatis, odio id accumsan tincidunt, eros ligula hendrerit urna, non ultricies nisi ex id ipsum.</p>
    <p>Curabitur sollicitudin fermentum justo nec vestibulum. Suspendisse potenti. Nullam nec sapien nec ipsum malesuada consequat. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>
  </div>
</div>

<!-- About Us Section -->
<div class="section" style="background-color: #f9f9f9;">
  <div class="content">
    <h2 class="section-title">Purpose and vision</h2>
    <p>DEPICT envisions leading the way in the application of artificial intelligence and medical imaging by developing, validating, and implementing advanced and cutting-edge methods. This enables us to offer tailored solutions that meet the individual needs of each patient. Through collaboration in an interdisciplinary team, we extract image information efficiently and with minimal impact on patients, contributing to better outcomes.</p>
  </div>
</div>

<!-- Vision Section -->
<div class="section" style="background-color: #d0d0d0;">
  <div class="content">
    <h2 class="section-title">Our Vision</h2>
    <p>We aspire to shape the future of medical imaging.</p>
    <ul class="vision-list">
      <li class="vision-item">The future of medical imaging is the right scan at the right time, tailored to the patient’s needs.</li>
      <li class="vision-item">The future of medical imaging is supported by automatic tools that quickly and efficiently gather all necessary information, seamlessly integrated and applied for diagnostics and within clinical settings.</li>
      <li class="vision-item">The future of medical imaging is based on interdisciplinary collaboration, the latest scanner technology, medical image analysis and artificial intelligence.</li>
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
