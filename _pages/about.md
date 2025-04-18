

{% include figure.liquid path="/assets/img/example.jpg" alt="Example Image" caption="This is an example caption." %}

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
  flex-direction: column; /* Sikrer lodret layout */
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 20px;
}

/* Stil til hero-tekst */
.hero-title {
  color: #EBF8FF; /* Hvid farve til tekst */
  font-weight: bold;
  font-size: 14em; /* Større tekststørrelse for titlen */
  margin-bottom: 0px; /* Tilføjer afstand mellem titlen og undertitlen */
}

.hero-subtitle {
  color: #EBF8FF; /* Hvid farve til tekst */
  font-size: 2em; /* Mindre tekststørrelse for undertitlen */
  margin-bottom: 100px; /* Tilføjer afstand mellem undertitlen og beskrivelsen */
}

.hero-description {
  color: #EBF8FF; /* Hvid farve til tekst */
  font-weight: bold;
  font-size: 2.7em; /* Større tekststørrelse for beskrivelsen */
  margin-bottom: 20px; /* Tilføjer afstand under beskrivelsen */
  max-width: 60%; /* Begrænser bredden for at tvinge linjeskift */
}

/* Stil for de to nederste sektioner */
.section {
  padding: 80px 20px; /* Tilpas padding efter behov */
  display: flex;
  justify-content: space-between;
}

.section-1 {
  background-color: #EFEBE2; /* Baggrundsfarve for første nederste sektion */
  display: flex; /* Tilpasning for centreret indhold */
  justify-content: center; /* Centrer indhold horisontalt */
  align-items: center; /* Centrer indhold vertikalt */
}

.section-2 {
  background-color: #FFFFFF; /* Baggrundsfarve for anden nederste sektion */
  display: flex;
  padding: 0 20px; /* Sidemargener for sektion 2 */
}

.column {
  flex: 1;
  padding: 20px;
}

.column-left {
  background-color: #EFEBE2; /* Baggrundsfarve for venstre kolonne i sektion 1 */
  text-align: center;
}

.column-right {
  background-color: #EFEBE2; /* Baggrundsfarve for højre kolonne i sektion 1 */
}

.column-left-2 {
  background-color: #FFFFFF; /* Baggrundsfarve for venstre kolonne i sektion 2 */
}

.column-right-2 {
  background-color: #FFFFFF; /* Baggrundsfarve for højre kolonne i sektion 2 */
  text-align: left; /* Venstrestil tekst i sektion 2, kolonne 2 */
}

.column-content {
  padding: 20px;
  text-align: center; /* Standard centreret tekst i sektion 2 */
}

.column-content.left-align {
  text-align: left; /* Venstrestil al tekst i sektion 2, kolonne 1 */
}

.column-content.right-align {
  text-align: left; /* Venstrestil al tekst i sektion 2, kolonne 2 */
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

.column p.left-align {
  text-align: left; /* Venstrestil al tekst i sektion 2, kolonne 1 */
}

.column img {
  max-width: 100%; /* Juster størrelsen på billedet efter behov */
  height: auto;
  display: block;
  border-radius: 0px;
  margin-top: 20px;
}

.small-image {
  max-width: 30%; /* Juster størrelsen kun for billedet med klassen "small-image" */
}

.bold-text {
  font-weight: bold;
  color: #FFFFFF; /* Hvid farve til fed tekst */
  font-size: 1.6em; /* Større tekststørrelse */
}

</style>

<!-- Hero Section with Large Image -->
<div class="hero-section">
    <img src="/assets/img/Utekst.jpg" alt="Forsidebillede" class="hero-image">
    <div class="hero-overlay">
        <h1 class="hero-title">DEPICT</h1>
        <p class="hero-subtitle">Center for AI and Medical Imaging</p>
        <h2 class="hero-description">We shape the future of diagnostic imaging to ensure the highest possible value for each individual patient</h2>
    </div>
</div>

<!-- Section 1 -->
<div class="section section-1">
    <div class="column column-left">
        <div class="column-content bold-text">
            <p>Our vision is to lead the way in the application of artificial intelligence and medical imaging by developing, validating, and implementing advanced and cutting-edge methods.</p>
            <img src="/assets/img/Rund7.jpg" alt="Rund" class="column-image small-image">
        </div>
    </div>
    <div class="column column-right">
        <div class="column-content">
            <img src="/assets/img/Amailie.jpg" alt="Amailie" class="column-image">
        </div>
    </div>
</div>

<!-- Section 2 -->
<div class="section section-2">
    <div class="column column-left-2">
        <div class="column-content left-align">
            <h3>Located</h3>
            <p>Rigshospitalet</p>
            <p>Department of Clinical Physiology and Nuclear Medicine</p>
            <p>Department of Radiology and Scanning</p>
        </div>
    </div>
    <div class="column column-right-2">
        <div class="column-content right-align">
            <h3>Sektion 2 - Højre Kolonne</h3>
            <p>Dette er højre kolonne i sektion 2. Du kan tilpasse indholdet her.</p>
        </div>
    </div>
</div>
