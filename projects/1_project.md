<style>
  body {
    background-color: #E6DED0;
    margin: 0;
    padding: 0;
    font-size: 16px; /* Justerer grundskriftstørrelsen for bedre læsbarhed på mobil */
    line-height: 1.6;
  }
  .custom-container {
    background-color: #E6DED0;
    padding: 20px; /* Forenklet padding for alle sider */
    margin: 0; /* Fjerner margener */
    box-sizing: border-box; /* Sikrer at padding er inkluderet i bredde/højde beregninger */
  }
  .post-title {
    font-weight: bold;
    color: #062A40;
    font-size: 2em; /* Justerer titelens skriftstørrelse */
    margin-top: 0; /* Fjerner standard top-margin */
    margin-bottom: 10px; /* Justerer bundmargin */
  }
  .custom-contact-box {
    background-color: #F4F0EB;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin-top: 20px; /* Øger top-margin for bedre adskillelse */
  }
  .custom-contact-box h4.small-header {
    color: #062A40;
    font-weight: bold;
    font-size: 1.2em; /* Justerer skriftstørrelse for header */
    margin-bottom: 10px;
  }
  .custom-contact-box .contact-item {
    margin-bottom: 8px; /* Justerer bundmargin for kontakt elementer */
  }
  article {
    font-size: 1em; /* Justerer skriftstørrelse for artikeltekst */
  }
  .figure-column {
    padding-right: 0; /* Fjerner højre padding for figurer for at udnytte pladsen bedre */
    margin-top: 20px; /* Øger top-margin for figurer */
  }

  /* Medieforespørgsel for mindre skærme (mobiltelefoner) */
  @media only screen and (max-width: 768px) {
    .custom-container {
      padding: 10px; /* Justerer padding for hele containeren på mindre skærme */
    }
    .figure-column, .custom-contact-box {
      margin-left: 0; /* Fjerner venstre margin på figurer og kontaktboks på mindre skærme */
      margin-right: 0; /* Fjerner højre margin på figurer og kontaktboks på mindre skærme */
    }
    .custom-contact-box {
      padding: 15px; /* Justerer padding for kontaktboksen på mindre skærme */
    }
    .custom-contact-box h4.small-header {
      font-size: 1em; /* Justerer skriftstørrelse for header på mindre skærme */
    }
  }
</style>

<div class="custom-container">
  <div class="post">
    <header class="post-header">
      <h1 class="post-title">{{ page.title }}</h1>
      <p class="post-description">{{ page.description }}</p>
    </header>

    <article>
      <div class="row">
        <div class="col-md-7">
          <strong>Introduction</strong>
          <p>The aim of this project is to enhance the diagnostic potential of whole-body Positron Emission Tomography/Computed Tomography (PET/CT) imaging by creating personalized synthetic healthy PET baselines using advanced Deep Learning techniques.</p>

          <strong>Project Background</strong>
          <p>Whole-body PET/CT imaging with FDG tracers is an invaluable diagnostic tool widely used in hospitals for detecting, diagnosing, and monitoring various diseases. However, standard analysis methods lack personalized healthy control images, reducing their precision and limiting the full diagnostic and prognostic potential of PET/CT imaging. This project addresses this limitation by introducing advanced Deep Learning techniques to synthesize personalized PET images based on the patient's own whole-body CT scans. This approach enables the development of images that reflect the individual patient's anatomical and physiological characteristics, increasing the accuracy of differentiating between normal and diseased states.</p>

          <strong>Project Potential</strong>
          <p>The project has the potential to detect deviations and subtle changes in organ uptake patterns by comparing the patient's digital twin with the actual PET scan. For example, in diabetes, a personalized healthy PET image can assess the disease by comparing it to the actual observed uptake. This project represents an innovative approach to improving diagnostic analysis methods, enhancing the accuracy of diagnoses, and increasing the effectiveness of treatment for individual patients.</p>
        </div>

        <div class="col-md-5 figure-column">
          {% include figure.liquid loading="eager" path="assets/img/Billede_ projekt 1.jpg" title="Example image" class="img-fluid rounded z-depth-1" %}

          <div class="caption mt-3">
            <p><strong>Figure 1:</strong> Application of healthy PET for lymphoma detection. From left: CT, PET, sbPET: Synthetic healthy PET image, Abnormality: difference between PET and synthetic PET, Segmentation: identified cancerous areas.</p>
          </div>

          <div class="custom-contact-box mt-4 border rounded shadow-sm">
            <h4 class="small-header">Contact Information</h4>
            <div class="contact-item">
              <strong>Name:</strong>
              <span>Christian Hinge</span>
            </div>
            <div class="contact-item">
              <strong>Email:</strong>
              <span><a href="mailto:christian.hinge@regionh.dk">christian.hinge@regionh.dk</a></span>
            </div>
            <div class="contact-item">
              <strong>Location:
