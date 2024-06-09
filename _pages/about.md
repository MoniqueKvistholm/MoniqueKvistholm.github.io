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
    .column {
      float: left;
      width: calc(50% - 20px); /* Juster bredden efter dine behov */
      margin: 0 10px; /* Tilføj margin til venstre og højre for at skabe et mellemrum */
    }
    .clearfix::after {
      content: "";
      clear: both;
      display: table;
    }
  </style>
</head>

<article>
  <!-- Placeholder til billede -->
  <div class="image-placeholder">
    <img src="{{ site.baseurl }}/assets/img/Forsidebillede2.jpg" alt="" class="full-width-image">
  </div>

  <div class="image-placeholder">
    <img src="{{ site.baseurl }}/assets/img/paceholder3.jpg" alt="" class="full-width-image">
  </div>

  <!-- Første spalte -->
  <div class="column">
    <h2>Reach out</h2>
    <p>Herlev og Gentofte Hospital, Afdeling for Røntgen og Skanning<br>
    Borgermester Ib Juuls Vej 17, 2730 Herlev<br><br>
    
    Bispebjerg og Frederiksberg Hospital, Røntgenafdelingen<br>
    Nielsine Nielsens Vej 41A, indgang 7A, 2400 København NV</p>
  </div>
  
  <!-- Anden spalte -->
  <div class="column">
    <p>We are experienced in and have great success with applying for grants with our partners. In addition, RAIT also offers commercial services such as validation of algorithms within a Danish clinical context.<br><br>
    
    Please reach out for more information.</p>
  </div>
</article>
