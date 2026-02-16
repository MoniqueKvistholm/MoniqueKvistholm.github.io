---
layout: page2
permalink: /github/
title: GitHub
nav: true
nav_order: 5
---


<!-- Hero Section with Background Image -->
<div class="hero-section">
  <div class="hero-overlay">
    <!-- Venstre side -->
    <div class="content-container">
      

      <div style="height: 50px;"></div>
      <!-- Publications Title -->
      <h1 class="hero-title">GitHub</h1>
      
      <div style="height: 20px;"></div>
      <!-- Introduction text -->
      <span class="hero-text">
        Explore the DEPICT project's official GitHub repositories. Click the button below to access research materials, code, and other resources related to the projects.
      </span>


      <div style="height: 70px;"></div>

      <!-- Links -->
      <div class="links-container">
        <a href="https://github.com/DEPICT-RH" class="styled-link">Visit DEPICT on GitHub</a>
      </div>
    </div>

    <!-- Højre side (tom) -->
    <div class="empty-right"></div>
  </div>
</div>


<style>
  /* Hero Section */
  .hero-section {
    position: relative;
    width: 100%;
    height: 100vh; /* Fylder hele skærmen */
    overflow: hidden; /* Sørger for at billedet ikke overskrider containeren */
    margin: 0; /* Fjern margin på body for at fjerne side margin */
    background-image: url('/assets/img/Background_GitHub5.png'); /* Sætter baggrundsbilledet */
    background-size: cover; /* Sørger for at billedet fylder hele skærmen */
    background-position: center; /* Centrerer billedet */
  }

  .hero-overlay {
    display: flex; /* Gør det muligt at opdele i to sektioner */
    flex-direction: row; /* Vandret opdeling */
    height: 100%;
    color:rgb(42, 74, 114); /* Tekstfarve hvid */
  }

  /* Venstre side */
  .content-container {
    flex: 1; /* Fylder venstre halvdel */
    padding: 40px; /* Indholdsmargin */
    display: flex;
    flex-direction: column;
    justify-content: flex-start; /* Juster indholdet til toppen */
    max-width: 50%; /* Maksimal bredde for at holde det i venstre side */
  }

  /* Højre side */
  .empty-right {
    flex: 1; /* Fylder højre halvdel */
  }

  /* Justering af tekst og links */
  .hero-title {
    font-size: 2em;
    margin: 0 0 10px;
    text-align: left;
    font-weight: bold; /* Gør overskriften fed */
    color: rgb(42, 74, 114); /* Sørger for at overskriften er hvid */
  }

  .hero-text {
    font-size: 1.5em;
    margin-bottom: 20px;
    text-align: left;
    color: rgb(42, 74, 114); /* Sørger for at teksten er hvid */
  }

  .links-container {
    margin-top: 20px;
    text-align: center; /* Sørger for centrering */
    width: 100%; /* Fylder bredden */
    max-width: 700px; /* Gør containeren lidt bredere */
  }


  .styled-link {
    display: inline-block;
    padding: 15px 30px;
    font-size: 1.2em; /* Forstør skriftstørrelsen */
    background-color: rgb(42, 74, 114);
    color:rgb(210, 214, 220);
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
  }

  .styled-link:hover {
    background-color:rgb(19, 33, 49);
    text-decoration: none; /* Bevar ingen streg under link */
    color: white;
  }

  /* Responsive Design for Smaller Screens */
  @media (max-width: 768px) {
    .hero-overlay {
      flex-direction: column; /* Ændrer layout til lodret */
      text-align: center; /* Centrerer tekst og links */
    }

    .content-container {
      max-width: 100%; /* Fylder hele bredden */
      padding: 20px; /* Mindre padding for små skærme */
    }

    .hero-title {
      font-size: 1.5em; /* Reducer fontstørrelsen for titlen */
      text-align: center; /* Centrer titlen */
    }

    .hero-text {
      font-size: 1.2em; /* Reducer fontstørrelsen for teksten */
      text-align: center; /* Centrer teksten */
    }

    .styled-link {
      font-size: 1em; /* Reducer fontstørrelsen */
      padding: 10px 20px; /* Mindre padding for små skærme */
      width: 90%; /* Lad knappen fylde næsten hele bredden */
      max-width: 300px; /* Gør knappen mindre */
    }
  }

  /* ---------- DARK MODE: keep GitHub like LIGHT ---------- */

  html[data-theme="dark"] body {
    background-color: #ffffff !important;
  }

  /* Behold baggrundsbilledet */
  html[data-theme="dark"] .hero-section {
    background-image: url('/assets/img/Background_GitHub5.png') !important;
    background-size: cover !important;
    background-position: center !important;
  }

  /* Behold samme tekstfarver som light */
  html[data-theme="dark"] .hero-title,
  html[data-theme="dark"] .hero-text {
    color: rgb(42, 74, 114) !important;
  }

  /* Behold samme knapfarver */
  html[data-theme="dark"] .styled-link {
    background-color: rgb(42, 74, 114) !important;
    color: rgb(210, 214, 220) !important;
  }

  html[data-theme="dark"] .styled-link:hover {
    background-color: rgb(19, 33, 49) !important;
    color: #ffffff !important;
  }

  /* Fjern evt. dark overlay fra theme */
  html[data-theme="dark"] .hero-overlay {
    background: transparent !important;
  }

  /* ---------- END ---------- */

</style>
