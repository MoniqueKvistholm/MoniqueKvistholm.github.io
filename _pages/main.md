---
layout: page2
title: Main
permalink: /
---

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
}

/* Hero-sektionen */
.hero-section {
  position: relative;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.hero-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

/* Overlay til hero-sektionen */
.hero-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 20px;
  background-color: rgba(0, 0, 0, 0.5); /* Mørk overlay */
}

/* Stil til hero-tekst */
.hero-title {
  color: #EBF8FF;
  font-weight: bold;
  font-size: 3em; /* Tilpasset størrelse */
  margin-bottom: 10px;
}

.hero-subtitle {
  color: #EBF8FF;
  font-size: 2em; /* Tilpasset størrelse */
  margin-bottom: 20px;
}

.hero-description {
  color: #EBF8FF;
  font-weight: bold;
  font-size: 1.5em; /* Tilpasset størrelse */
  max-width: 80%; /* Begrænser bredden for at tvinge linjeskift */
}

/* Stil for de to nederste sektioner */
.section {
  padding: 60px 20px; /* Tilpas padding efter behov */
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap; /* Tillader brud på linjerne */
}

.section-1 {
  background-color: #EFEBE2;
}

.section-2 {
  background-color: #FFFFFF;
  display: flex;
  padding: 20px; /* Sidemargener for sektion 2 */
  flex-wrap: wrap; /* Tillader brud på linjerne */
}

.column {
  flex: 1;
  padding: 20px;
  box-sizing: border-box; /* Forhindrer padding i at påvirke den totale bredde */
}

.column-left {
  text-align: center;
}

.column-right {
  text-align: center;
}

.column-left-2 {
  background-color: #FFFFFF;
}

.column-right-2 {
  background-color: #FFFFFF;
}

.column-content {
  padding: 20px;
}

.column-content.left-align {
  text-align: left;
}

.column-content.right-align {
  text-align: left;
}

.column h3 {
  font-size: 1.8em;
  color: #062A40;
  margin-bottom: 10px;
  font-weight: bold; /* Fed skrift */
}

.column p {
  font-size: 1em;
  line-height: 1.4; /* Reducér linjeafstand */
  color: #062A40;
  /* Beholder standard centreret tekst til sektion 2, kolonne 1 */
}

.column img {
  max-width: 100%;
  height: auto;
  display: block;
  border-radius: 0px;
  margin-top: 20px;
}

.small-image {
  max-width: 70%; /* Juster størrelsen kun for billedet med klassen "small-image" */
}

.bold-text {
  font-weight: bold;
  color: #FFFFFF;
  font-size: 1.6em; /* Større tekststørrelse */
}

/* Media queries til mobiltilpasning */
@media (max-width: 768px) {
  .hero-title {
    font-size: 2.5em;
  }

  .hero-subtitle {
    font-size: 1.5em;
    margin-bottom: 10px;
  }

  .hero-description {
    font-size: 1em;
    max-width: 90%;
  }

  .section {
    padding: 30px 10px;
  }

  .section-1, .section-2 {
    flex-direction: column;
    align-items: center;
  }

  .column {
    flex: 1 1 100%;
    text-align: center;
  }

  .small-image {
    max-width: 50%;
  }
}

/* Media queries til meget små skærme */
@media (max-width: 480px) {
  body, html {
    margin: 0;
    padding: 0;
    height: 100%;
    overflow-x: hidden;
  }

  .hero-section {
    position: relative;
    height: 100vh;
    overflow: hidden;
  }

  .hero-image {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
  }

  .hero-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 10px;
    box-sizing: border-box;
    z-index: 1;
  }

  .hero-title {
    font-size: 1.8em;
    margin: 0;
  }

  .hero-subtitle {
    font-size: 1.2em;
    margin-bottom: 10px;
  }

  .hero-description {
    font-size: 1em;
    max-width: 100%;
  }

  .section {
    padding: 20px 10px;
  }

  .section-1, .section-2 {
    flex-direction: column;
    align-items: center;
  }

  .column {
    flex: 1 1 100%;
    text-align: center;
  }

  .small-image {
    max-width: 90%;
  }

  .column img {
    max-width: 90%;
    margin: 10px 0;
  }

  .bold-text {
    font-size: 1.2em;
  }

  .column h3 {
    font-size: 1.4em;
  }

  .column p {
    font-size: 0.9em;
  }
}
</style>

<div class="hero-section">
  <img src="{{site.baseurl}}/assets/images/forsidebillede.jpg" alt="Hero Image" class="hero-image">
  <div class="hero-overlay">
    <h1 class="hero-title">DIN NORMA</h1>
    <h2 class="hero-subtitle">Dit Læringscenter</h2>
    <p class="hero-description">En beskrivelse af dit læringscenter, dets mission og vision.</p>
  </div>
</div>

<!-- Sektion 1 -->
<div class="section section-1">
  <div class="column column-left">
    <div class="column-content left-align">
      <h3>Om Os</h3>
      <p class="left-align">Kort tekst om læringscenteret, dens formål og hvem det henvender sig til.</p>
    </div>
  </div>
  <div class="column column-right">
    <img src="{{site.baseurl}}/assets/images/ønsker forside.jpg" alt="Om Os Billede" class="small-image">
  </div>
</div>

<!-- Sektion 2 -->
<div class="section section-2">
  <div class="column column-left-2">
    <div class="column-content right-align">
      <h3>Vores Ydelser</h3>
      <p class="left-align">Beskrivelse af de ydelser og tilbud, læringscenteret har.</p>
    </div>
  </div>
  <div class="column column-right-2">
    <div class="column-content">
      <img src="{{site.baseurl}}/assets/images/ønsker forside.jpg" alt="Vores Ydelser Billede">
    </div>
  </div>
</div>
