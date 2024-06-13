---
layout: forside2
title: Main
permalink: /
---

<head>
  <style>
    /* CSS-regler til styling af denne side */
    .image-placeholder {
      /* Tilpas dine styling-regler her */
    }

    /* Tilføj flere regler efter behov */

    .clearfix {
      display: flex;
      justify-content: space-between; /* Justerer pladsen mellem kolonnerne */
      padding: 20px;
    }
    
    .column {
      flex: 1; /* Fordeler lige meget plads til hver kolonne */
      margin: 30px; /* Tilføjer lidt margin omkring kolonnerne */
    }

    .column p {
      margin: 0 0 10px; /* Tilføjer margin nedenunder afsnit */
    }
  </style>
</head>

<article>
  <!-- Placeholder til billede -->
  <div class="image-placeholder">
    <img src="{{ site.baseurl }}/assets/img/Forsidebillede.jpg.jpg" alt="" class="full-width-image">
  </div>

  <div class="image-placeholder">
    <img src="{{ site.baseurl }}/assets/img/paceholder baggrund.jpg" alt="" class="full-width-image">
  </div>
  <div class="image-placeholder">
    <img src="{{ site.baseurl }}/assets/img/paceholder baggrund.jpg" alt="" class="full-width-image">
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
</article>
