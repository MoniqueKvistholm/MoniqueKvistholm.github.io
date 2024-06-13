<head>
  <style>
    /* CSS-regler til styling af denne side */
    .image-placeholder {
      overflow: hidden; /* Sikrer, at billedet ikke overskrider sin container */
      margin-bottom: -10px; /* Juster denne værdi efter behov for at reducere mellemrummet */
    }

    .full-width-image {
      width: 100%;
      height: auto;
      display: block;
    }

    .clearfix {
      display: flex;
      justify-content: space-between; /* Justerer pladsen mellem kolonnerne */
      padding: 40px; /* Generel padding omkring indhold */
      margin: 0 auto; /* Centrerer indholdet horisontalt */
      max-width: 1200px; /* Sætter en maksimal bredde for indholdet */
    }

    .column {
      flex: 1; /* Fordeler lige meget plads til hver kolonne */
      margin: 0 20px; /* Øger margenen omkring kolonnerne */
      padding: 20px; /* Tilføjer padding for at øge afstanden fra kanten af billedet */
      box-sizing: border-box; /* Sørger for at padding ikke øger elementets bredde */
      background-color: #f0f0f0; /* Eksempel på baggrundsfarve */
      border: 1px solid #ddd; /* Eksempel på kant omkring kolonner */
    }

    .column p {
      margin: 0 0 15px; /* Tilføjer margin nedenunder afsnit */
    }
  </style>
</head>

<article>
  <!-- Placeholder til billede -->
  <div class="image-placeholder">
    <img src="{{ site.baseurl }}/assets/img/Forsidebillede.jpg.jpg" alt="" class="full-width-image">
  </div>

  <div class="image-placeholder">
    <img src="{{ site.baseurl }}/assets/img/side22.jpg" alt="" class="full-width-image">
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
