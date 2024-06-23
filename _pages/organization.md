/* Tilføjet styling for at justere størrelsen af .leader-box */
.leader-box {
  max-width: 200px; /* Juster bredden efter behov */
  margin-bottom: 100px; /* Øget margin mellem hver leader box */
  padding: 10px; /* Tilføj padding inden i leader box */
  display: flex; /* Flexbox for at justere layout */
  align-items: center; /* Centrer indhold vertikalt */
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
  text-align: left; /* Venstrejuster overskriften */
  padding-top: 50px; /* Juster afstanden til overskriften "Centerledere" */
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
  text-align: left; /* Venstrestil tekst */
}

.centerledere-section img {
  width: 200px; /* Juster størrelsen på lederbillederne */
  height: 200px;
  margin-right: 20px; /* Margin til højre for at adskille billedet fra teksten */
  border-radius: 0; /* Fjern afrundede hjørner */
}

/* Juster overskriftsstørrelse for Centerledere */
.centerledere-section h3 {
  font-size: 2em; /* Større overskriftsstørrelse */
  margin-bottom: 20px; /* Mindre margin nederst i overskriften */
}

.col-md-6:first-child {
  margin-right: 50px; /* Tilføj margin til højre for den første kolonne */
}
