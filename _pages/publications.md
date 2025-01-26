---
layout: page2
permalink: /publications/
title: Publications
nav: true
nav_order: 4
---

<!-- Hero Section with Background Image -->
<div class="hero-section">
  <div class="hero-overlay">
    <!-- Publications Title -->
    <div style="height: 31px;"></div>
    <h1 class="hero-title">Publications</h1>
    <div style="height: 20px;"></div>

    <!-- Introduction text -->
    <span class="hero-text">Publications from DEPICT can be found in the departments' research registration system, PURE.</span>
    <div style="height: 30px;"></div>

    <!-- Links -->
    <div class="links-container">
      <a href="https://research.regionh.dk/da/organisations/afdeling-for-r%c3%b8ntgen-og-skanning/publications/" class="styled-link">Research from the Department of Radiology and Imaging</a>
      <div style="height: 20px;"></div>
      <a href="https://research.regionh.dk/da/organisations/afdeling-for-klinisk-fysiologi-og-nuklearmedicin" class="styled-link">Research from the Department of Clinical Physiology and Nuclear Medicine</a>
    </div>
  </div>
</div>

<style>
  /* Hero Section */
  .hero-section {
    position: relative;
    width: 100%;
    height: 100vh; /* Fylder hele skærmen */
    overflow: hidden; /* Sørger for at billede ikke overskrider containeren */
    margin: 0; /* Fjern margin på body for at fjerne side margin */
    background-image: url('/assets/img/Background_Publications7.png'); /* Sætter baggrundsbilledet */
    background-size: cover; /* Sørger for at billedet fylder hele skærmen */
    background-position: center; /* Centrerer billedet */
  }

  .hero-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: none;
    color: white; /* Tekstfarve hvid */
    display: flex;
    flex-direction: column;
    justify-content: flex-start; /* Juster teksten opad */
    z-index: 2; /* Sørger for at tekst og links er ovenpå billedet */
    padding: 40px; /* Justering af afstand */
  }

  .hero-title {
    font-size: 2em; /* Større font til overskriften */
    margin: 0 0 10px; /* Afstand under overskriften */
    color: #112334; /* Sørger for at overskriften er hvid */
    text-align: left; /* Venstrestil overskriften */
    font-weight: bold; /* Gør overskriften fed */
  }

  .hero-text {
    font-size: 1.5em;
    color: #112334; /* Sørger for at introduktionsteksten er hvid */
    margin-bottom: 20px; /* Plads mellem introduktionstekst og links */
    text-align: left; /* Venstrestil introduktionsteksten */
  }

  .links-container {
    display: flex;
    flex-direction: row; /* Placer linksene side om side */
    align-items: stretch; /* Sørger for, at linksene strækkes til samme højde */
    justify-content: center; /* Centrer linksene horisontalt */
    width: 100%;
    max-width: 1200px; /* Reducer containerbredden */
    margin: 0 auto;
    gap: 20px; /* Mellemrum mellem boksene */
    flex-wrap: wrap; /* Tillad wrap til næste række for små skærme */
}

.styled-link {
    font-size: 1.2em;
    display: flex; /* Brug flex for at centrere teksten */
    align-items: center; /* Centrer teksten vertikalt */
    justify-content: center; /* Centrer teksten horisontalt */
    padding: 10px 30px; /* Øget horisontal padding for at gøre boksene mere aflange */
    margin: 10px 0;
    background-color: #648bbb;
    color: white;
    text-align: center;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
    width: 350px; /* Øget bredde for at gøre dem længere */
    height: auto; /* Gør højden fleksibel baseret på indholdet og padding */
}

.styled-link:hover {
    background-color: rgb(42, 74, 114);
    text-decoration: none;
    color: white;
}


/* Responsive Design for Smaller Screens */
@media (max-width: 768px) {
    .styled-link {
        width: 90%; /* Fyld næsten hele bredden på små skærme */
    }

    .links-container {
        flex-direction: column; /* Skift til kolonnevisning på små skærme */
        gap: 10px;
    }
}

</style>
