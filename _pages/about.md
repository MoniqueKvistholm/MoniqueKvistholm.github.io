---
layout: forside2
title: Main
permalink: /
---

<head>
  <style>
    /* CSS-regler til styling af denne side */
    .image-placeholder {
      width: 100%;
      position: relative;
      margin: 0;
      padding: 0;
    }

    .full-width-image {
      width: 100%;
      height: auto;
      display: block;
    }

    .clearfix {
      display: flex;
      justify-content: space-between;
      margin: 20px auto; /* Giver lidt margin over og under sektionen */
      max-width: 1200px;
      padding: 0 20px;
      box-sizing: border-box;
    }

    .column {
      flex: 1;
      margin: 0 20px;
      padding: 20px;
      box-sizing: border-box;
    }

    .column p {
      margin: 0 0 15px;
    }
  </style>
</head>

<article>
  <!-- Placeholder til billede -->
  <div class="image-placeholder">
    <img src="{{ site.baseurl }}/assets/img/Forsidebillede.jpg" alt="Forsidebillede" class="full-width-image">
  </div>

  <div class="clearfix">
    <div class="column">
      <h2>DEPICT</h2>
      <p>Information om DEPICT - Center for AI in Medical Imaging.</p>
      <p>Rigshospitalet</p>
      <p>Department of Clinical Physiology and Nuclear Medicine</p>
      <p>Department of Radiology and Scanning</p>
    </div>
    <div class="column">
      <h2>Om Os</h2>
      <p>Her kan du skrive noget om dig selv...</p>
      <p>Information om afdelingens mål og projekter.</p>
      <p>Detaljer om forskning og udvikling.</p>
      <p>Kontaktinformation og yderligere ressourcer.</p>
    </div>
  </div>

  <div class="image-placeholder">
    <img src="{{ site.baseurl }}/assets/img/side22.jpg" alt="Sidebillede" class="full-width-image">
  </div>
</article>
