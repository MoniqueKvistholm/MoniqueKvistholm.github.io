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
    <div style="height: 50px;"></div>
    <h1 class="hero-title">Publications</h1>
    <div style="height: 20px;"></div>

    <!-- Introduction text -->
    <span class="hero-text">Publications from DEPICT can be found in the departments' research registration system, PURE.</span>
    <div style="height: 100px;"></div>

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
    background-image: url('/assets/img/Background_Publications.png'); /* Sætter baggrundsbilledet */
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
    color: white; /* Sørger for at overskriften er hvid */
    text-align: left; /* Venstrestil overskriften */
    font-weight: bold; /* Gør overskriften fed */
  }

  .hero-text {
    font-size: 1.5em;
    color: white; /* Sørger for at introduktionsteksten er hvid */
    margin-bottom: 20px; /* Plads mellem introduktionstekst og links */
    text-align: left; /* Venstrestil introduktionsteksten */
  }

  .links-container {
    display: flex;
    flex-direction: column;
    align-items: center; /* Centrer linksene horisontalt */
    justify-content: center; /* Centrer linksene vertikalt */
    width: 100%; /* Sørger for at containeren fylder hele bredden */
    max-width: 2000px; /* Begræns bredden af containeren */
    margin: 0 auto; /* Centrer containeren horisontalt */
  }

  .styled-link {
    font-size: 1.2em;
    display: block;
    padding: 25px 200px; /* Øget padding for at gøre kasserne mere aflange */
    margin: 10px 0;
    background-color: #648bbb;
    color: white; /* Sørger for at linkene er hvid */
    text-align: center;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
    width: 100%; /* Indsæt en fast bredde, så de ikke fylder hele bredden */
    max-width: 700px; /* Maksimal bredde, så de ikke bliver for brede */
  }

  .styled-link:hover {
    background-color: rgb(42, 74, 114);
    text-decoration: none; /* Bevar ingen streg under link */
    color: white;
  }

  /* Responsive Design for Smaller Screens */
  @media (max-width: 768px) {
    .styled-link {
      padding: 15px 20px; /* Reducer padding til mindre skærme */
      font-size: 1em; /* Reducer fontstørrelsen */
      max-width: 90%; /* Lad linkboksene fylde næsten hele bredden */
    }

    .hero-title {
      font-size: 1.5em; /* Reducer fontstørrelsen for titlen */
    }

    .hero-text {
      font-size: 1.2em; /* Reducer fontstørrelsen for teksten */
    }
  }
</style>
