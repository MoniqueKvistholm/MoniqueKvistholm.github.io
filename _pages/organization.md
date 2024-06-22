---
layout: page2
permalink: /organization/
title: Organization
nav: false
nav_order: 
---

<style>
  /* Tilføjet styling for at justere størrelsen af .leader-box */
  .leader-box {
    max-width: 550px; /* Juster bredden efter behov */
    margin-bottom: 30px; /* Tilføj margin mellem hver leader box */
    padding: 20px; /* Tilføj padding inden i leader box */
  }

  /* Fjern margin og padding fra body */
  body {
    margin: 0;
    padding: 0;
  }

  /* Stil for hver sektion */
  .section {
    width: 100vw;
    margin-left: calc(50% - 50vw);
    padding-top: 0; /* Fjern top padding for at sikre ingen ekstra plads øverst */
  }

  /* Stil for hver sektion med specifik baggrundsfarve */
  .organization-section {
    background-color: #EBF8FF; /* Ændre baggrundsfarven efter behov */
  }

  .centerledere-section {
    background-color: #f2f2f2;
  }

  .styregruppe-section {
    background-color: #d0d0d0;
  }

  .ai-forskningsledere-section {
    background-color: #c0c0c0;
  }

  .bestyrelse-section {
    background-color: #b0b0b0;
  }

  /* Stil for indhold i hver sektion */
  .section-content {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }

  /* Tilpasning til centerledere-sektion */
  .centerledere-section .container {
    padding: 20px 0; /* Tilføj lidt padding over og under containeren */
  }

  .centerledere-section .leader-box {
    margin-bottom: 50px; /* Øget margin mellem hver leader box */
  }

  .centerledere-section img {
    width: auto; /* Automatisk bredde tilpasset størrelsen af billedet */
    height: 200px; /* Fast højde for at holde størrelsen ensartet */
    margin-right: 20px; /* Margin til højre for at adskille billedet fra teksten */
  }

  /* Juster overskriftsstørrelse for Centerledere */
  .centerledere-section h3 {
    font-size: 2em; /* Større overskriftsstørrelse */
    margin-bottom: 20px; /* Mindre margin nederst i overskriften */
    text-align: center; /* Centrer overskriften */
  }

  /* Stil for teksten ved siden af billedet */
  .centerledere-section .leader-details {
    flex: 1;
  }

  .centerledere-section .leader-details h4 {
    margin-top: 0; /* Fjern topmargin for at få teksten til at starte ved billedet */
  }
</style>

<!-- Ny Baggrundsfarve for Organization sektion -->
<div class="section organization-section">
  <div class="section-content">
    <h2>Organization</h2>
    <strong style="font-size: 1.5em;">Organizationdiagram</strong>
    <img src="/assets/img/Organisationsdiagram.png" alt="Organizational Diagram">
    <p>*Her indsættes et organisationsdiagram*</p>
  </div>
</div>

<!-- Ny Baggrundsfarve for Centerledere sektion -->
<div class="section centerledere-section">
  <div class="section-content">
    <h3 style="color: #004062; text-align: center;">Centerledere</h3>
    <div class="container mt-5">
      <div class="row">
        <div class="col-md-6">
          <div class="leader-box d-flex">
            <div class="col-4">
              <img src="/assets/img/Portræt_Flemming.jpg" alt="Flemming Andersen" class="img-fluid rounded-0">
            </div>
            <div class="col-8 leader-details">
              <h4 class="mb-3">Flemming Andersen</h4>
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
          <div class="leader-box d-flex">
            <div class="col-4">
              <img src="/assets/img/Portræt_Adam.jpg" alt="Adam Espe Hansen" class="img-fluid rounded-0">
            </div>
            <div class="col-8 leader-details">
              <h4 class="mb-3">Adam Espe Hansen</h4>
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
</div>

<!-- Ny Baggrundsfarve for Styregruppe sektion -->
<div class="section styregruppe-section">
  <div class="section-content">
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
</div>

<!-- Ny Baggrundsfarve for AI Forskningsledere sektion -->
<div class="section ai-forskningsledere-section">
  <div class="section-content">
    <h3>AI Forskningsledere</h3>
    <ul>
      <li>Claes Ladefoged</li>
      <li>Michael Bachman</li>
    </ul>
  </div>
</div>

<!-- Ny Baggrundsfarve for Bestyrelse sektion -->
<div class="section bestyrelse-section">
  <div class="section-content">
    <h3>Bestyrelse</h3>
    <ul>
      <li>Malene Fischer</li>
      <li>Martin Lundsgaard</li>
    </ul>
  </div>
</div>
