---
layout: page2
permalink: /organization/
title: Organization
nav: false
nav_order: 
---

<style>
  /* Generel reset af margin og padding */
  body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif; /* Tilføj en standard skrifttype for bedre læsbarhed */
  }

  /* Container til at centrere sektioner */
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }

  /* Sektioner med forskellige baggrundsfarver */
  .organization-section, .centerledere-section, .leadership-section {
    padding-top: 50px;
    padding-bottom: 50px;
  }

  .organization-section {
    background-color: #EBF8FF;
  }

  .centerledere-section {
    background-color: #F8F5F5;
  }

  .leadership-section {
    background-color: #d0d0d0;
  }

  /* Styling for leader box */
  .leader-box {
    display: flex;
    flex-direction: column; /* Ændret til kolonnevisning på mindre skærme */
    align-items: flex-start;
    margin-bottom: 40px;
  }

  .leader-box img {
    width: 100%; /* Ændret til 100% for at være responsiv */
    max-width: 150px;
    height: auto; /* Tilpasser højden automatisk for at bevare billedforholdet */
    object-fit: cover;
    border-radius: 0%;
    margin-bottom: 20px; /* Ændret fra margin-right til margin-bottom på små skærme */
  }

  .leader-info {
    flex: 1;
  }

  /* Styling for overskrifter */
  h2, h3 {
    text-align: left;
    margin-bottom: 30px;
  }

  /* Styling for kontaktinformation */
  .contact-item {
    margin-bottom: 10px;
  }

  /* Responsive design */
  @media (max-width: 768px) {
    .container {
      padding: 10px; /* Reducer padding på små skærme */
    }

    .leader-box {
      flex-direction: column; /* Ændrer layout til kolonnevisning */
    }

    .leader-box img {
      width: 100%; /* Gør billedet responsivt */
      max-width: 100%;
      margin-bottom: 10px;
    }

    /* Styler for mindre skærme i leadership-sektionen */
    .leadership-section .row {
      flex-direction: column; /* Ændrer rækkefølge på kolonner til én kolonne */
    }

    .leadership-section .col-md-4 {
      margin-bottom: 20px; /* Tilføjer afstand mellem sektioner */
    }
  }
</style>

<!-- Organization sektion -->
<div class="organization-section">
  <div class="container">
    <h2>Organization</h2>
    <strong style="font-size: 1.5em;">Organizationdiagram</strong>
    <img src="/assets/img/Organisationsdiagram.png" alt="Organizational Diagram">
  </div>
</div>

<!-- Centerledere sektion -->
<div class="centerledere-section">
  <div class="container">
    <h3>Centerledere</h3>
    <div class="row">
      <div class="col-md-6">
        <div class="leader-box">
          <img src="/assets/img/Portræt_Flemming.jpg" alt="Flemming Andersen">
          <div class="leader-info">
            <h4>Flemming Andersen</h4>
            <div class="contact-item">
              <strong>Email:</strong>
              <span><a href="mailto:flemming.andersen@regionh.dk">flemming.andersen@regionh.dk</a></span>
            </div>
            <div class="contact-item">
              <strong>Tlf:</strong>
              <span>+45 35-45 81-43</span>
            </div>
            <div class="contact-item">
              <strong>Placering:</strong>
              <span>3982, Klinisk Fysiologi og Nuklearmedicin</span>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-6">
        <div class="leader-box">
          <img src="/assets/img/Portræt_Adam.jpg" alt="Adam Espe Hansen">
          <div class="leader-info">
            <h4>Adam Espe Hansen</h4>
            <div class="contact-item">
              <strong>Email:</strong>
              <span><a href="mailto:adam.espe.hansen@regionh.dk">adam.espe.hansen@regionh.dk</a></span>
            </div>
            <div class="contact-item">
              <strong>Tlf:</strong>
              <span>+45 35-45 84-60</span>
            </div>
            <div class="contact-item">
              <strong>Placering:</strong>
              <span>3023, Røntgen og Skanning</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Leadership sektion -->
<div class="leadership-section">
  <div class="container">
    <div class="row">
      <div class="col-md-4">
        <h3>Styregruppe</h3>
        <ul>
          <li>Malene Fischer</li>
          <li>Flemming Littrup Andersen</li>
          <li>Claes Ladefoged</li>
          <li>Adam Espe Hansen</li>
          <li>Michael Bachmann Nielsen</li>
          <li>Jonathan Carlsen</li>
          <li>Martin Lundsgaard</li>
          <li>Jann Mortensen</li>
          <li>Ida Robsøe</li>
          <li>Johnny Madelung</li>
        </ul>
      </div>
      <div class="col-md-4">
        <h3>AI Forskningsledere</h3>
        <ul>
          <li>Claes Ladefoged</li>
          <li>Michael Bachman</li>
        </ul>
      </div>
      <div class="col-md-4">
        <h3>Bestyrelse</h3>
        <ul>
          <li>Malene Fischer</li>
          <li>Martin Lundsgaard</li>
        </ul>
      </div>
    </div>
  </div>
</div>
