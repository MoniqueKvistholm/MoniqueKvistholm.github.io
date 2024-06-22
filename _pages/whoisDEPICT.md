<style>
  body {
    margin: 0; /* Fjern standard margener */
  }
  .hero-section {
    display: flex;
    align-items: center;
    height: 100vh; /* Fyld hele viewportens højde */
    background-color: #9DC0D1;
  }
  .hero-image {
    flex: 1;
    width: auto;
    height: 100%;
    object-fit: cover; /* Billede fylder hele højden */
  }
  .hero-content {
    flex: 1;
    padding: 40px 20px; /* Juster padding for at øge højden på boksen */
    text-align: center;
    color: #004062;
    background-color: #B5D3E7; /* Lysere blå baggrundsfarve */
    border-radius: 10px; /* Afrundede kanter */
  }
  .hero-content h1 {
    font-size: 2.5em; /* Mindre font-størrelse */
    font-weight: bold; /* Federe tekst */
    margin-bottom: 20px;
  }
  .hero-content p {
    font-size: 1.2em;
    line-height: 1.5;
  }
  .section {
    width: 100vw; /* Fyld viewportens bredde */
    padding: 40px 20px; /* Juster padding efter behov */
  }
  .content {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }
  .section-title {
    color: #004062;
    font-size: 1.8em; /* Mindre font-størrelse */
    font-weight: bold; /* Federe tekst */
    margin-bottom: 20px;
  }
  .vision-list {
    list-style-type: none;
    padding: 0;
  }
  .vision-item {
    background-color: #f2f2f2;
    border-radius: 5px;
    margin-bottom: 10px;
    padding: 20px;
  }
</style>
