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
  }

  /* Container til at centrere sektioner */
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }

  /* Sektioner med forskellige baggrundsfarver */
  .organization-section {
    background-color: #EBF8FF;
    padding-top: 50px;
    padding-bottom: 50px;
  }

  .centerledere-section {
    background-color: #F8F5F5;
    padding-top: 50px;
    padding-bottom: 50px;
  }

  .leadership-section {
    background-color: #d0d0d0;
    padding-top: 50px;
    padding-bottom: 50px;
  }

  /* Styling for leader box */
  .leader-box {
    display: flex;
    align-items: left;
    margin-bottom: 40px;
  }

  .leader-box img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border-radius: 0%;
    margin-right: 20px;
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
