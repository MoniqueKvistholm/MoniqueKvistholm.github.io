---
layout: default2
title: Normal Twin PET - Personalized Baseline for Whole-Body PET Analysis
description: PhD Project by Christian Hinge
img: assets/img/P15.jpg
importance: 1
category: 2026
related_publications: false
---

<style>
  body {
    background-color: #E6DED0; /* Background color for the entire page */
    margin: 0;
    padding: 0;
  }

  .custom-container {
    background-color: #E6DED0; /* Background color for the content */
    padding: 20px; /* General padding */
    margin: 0; /* Remove margins */
    margin-bottom: 40px; /* Extra bottom margin for additional space */
  }

  .post-title {
    font-weight: bold;
    color: #062A40; /* Color for the title */
    text-align: left; /* Left-align the title */
    font-size: 2.5em; /* Increase font size of the title */
    margin-top: 10px; /* Reduce top margin for the title */
    margin-bottom: 20px;
  }

  .custom-contact-box {
    background-color: #F4F0EB; /* Background color for the contact box */
    border: 1px solid #ddd; /* Border around the contact box */
    border-radius: 5px; /* Rounded corners */
    padding: 10px; /* Reduced padding inside the contact box */
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Shadow */
    margin-top: 20px; /* Add space above the contact box */
    margin-bottom: 10px; /* Reduced space below the contact box */
  }

  .custom-contact-box h4.small-header {
    color: #062A40; /* Color for the header in the contact box */
    font-weight: bold;
    font-size: 1em; /* Smaller font size for the header */
    margin-bottom: 15px; /* Increased bottom margin for the header to space from content */
  }

  .custom-contact-box .contact-item {
    margin-bottom: 8px; /* Increased bottom margin for contact items */
  }

  .custom-contact-box .contact-item strong {
    color: #555; /* Color for strong tags (e.g., 'Name:', 'Email:', etc.) */
    font-size: 0.9em; /* Smaller font size for strong tags */
  }

  .custom-contact-box .contact-item span {
    color: #333; /* Color for span tags (e.g., 'Christian Hinge', email link, etc.) */
    font-size: 0.9em; /* Smaller font size for span tags */
  }

  .custom-contact-box .contact-item:last-of-type {
    margin-bottom: 12px; /* Reduced margin below the last contact item */
  }

  .custom-contact-box .spacer {
    margin-bottom: 12px; /* Margin below the spacer to create more space */
  }

  article {
    font-size: 1.1em;
    line-height: 1.6;
  }

  .figure-column {
    padding-right: 15px; /* Right padding to separate figure from text */
  }

  .small-link {
    font-size: 0.8em; /* Smaller font size for the link */
  }

  .publication-link::before {
    content: '•'; /* Bullet point before the link */
    color: #062A40; /* Color of the bullet point */
    font-size: 1.2em; /* Size of the bullet point */
    margin-right: 8px; /* Space between the bullet point and the text */
    vertical-align: middle; /* Align bullet point with text */
  }

  /* Responsive design */
  @media (max-width: 768px) {
    .post-title {
      font-size: 1.8em; /* Smaller font size for the title on small screens */
    }

    .custom-container {
      padding: 10px; /* Reduced padding for small screens */
      margin: 0 10px; /* Add small margins for small screens */
    }

    .figure-column {
      padding-right: 0; /* Remove right padding on small screens */
    }

    .row {
      display: block; /* Stack columns vertically on small screens */
      margin: 0; /* Remove margin */
    }

    .col-md-7, .col-md-5 {
      width: 100%; /* Full width for columns on small screens */
      padding: 0; /* Remove padding inside columns on small screens */
    }
  }

  @media (max-width: 480px) {
    .post-title {
      font-size: 1.5em; /* Even smaller font size for the title on extra small screens */
    }

    .custom-contact-box h4.small-header {
      font-size: 0.9em; /* Smaller font size for contact box header */
      margin-bottom: 12px; /* Adjusted bottom margin for smaller screens */
    }

    article {
      font-size: 1em; /* Slightly smaller font size for article text */
    }

    .custom-container {
      padding: 0 10px; /* Add small side margins for extra small screens */
    }

    .figure-column {
      padding-right: 0; /* Remove right padding on extra small screens */
    }

    .row {
      display: block; /* Stack columns vertically on extra small screens */
      margin: 0; /* Remove margin */
    }

    .col-md-7, .col-md-5 {
      width: 100%; /* Full width for columns on extra small screens */
      padding: 0; /* Remove padding inside columns on extra small screens */
    }
  }

  /* ---------- DARK MODE ---------- */
  html[data-theme="dark"] body {
    background-color: #E6DED0 !important;
    color: var(--global-text-color) !important;
  }

  /* Behold DIN flotte beige custom-container, men gør teksten lys */
  html[data-theme="dark"] .custom-container {
    background-color: #E6DED0 !important;  /* behold beige */
    color: #0f172a !important;             /* mørk tekst på beige */
  }

  /* Tekst inde i content skal også være mørk på beige */
  html[data-theme="dark"] .custom-container h1,
  html[data-theme="dark"] .custom-container h2,
  html[data-theme="dark"] .custom-container h3,
  html[data-theme="dark"] .custom-container h4,
  html[data-theme="dark"] .custom-container p,
  html[data-theme="dark"] .custom-container strong,
  html[data-theme="dark"] .custom-container span,
  html[data-theme="dark"] .custom-container li {
    color: #0f172a !important;
  }

  /* Kontaktboksen: gør den stadig mørk eller lys? (jeg foreslår lys for at matche beige) */
  html[data-theme="dark"] .custom-contact-box {
    background-color: #F4F0EB !important; /* behold lys boks */
    border-color: rgba(0,0,0,0.15) !important;
    color: #0f172a !important;
  }

  /* Links på beige */
  html[data-theme="dark"] .custom-container a {
    color: #154360 !important; /* din theme blå */
  }
  /* ---------- END DARK MODE ---------- */
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
          <p>Whole-body PET/CT imaging is widely used for disease diagnosis and treatment assessment, but quantitative analysis is challenged by large interpatient variability caused by physiological FDG uptake patterns. Factors such as age, body composition, scanner type, and uptake time can obscure disease-related signals and limit diagnostic precision.</p>

          <strong>Project Background</strong>
          <p>This study presents a novel deep learning approach for generating personalized normal twin PET images based on the patient's own CT scans. The synthetic normal twin represents how the patient’s PET image would appear under healthy conditions and serves as an individualized reference baseline. By comparing PET images with their normal twins, the method enables confounder correction and robust anomaly detection. The approach for generating the normal twin is illustrated in Figure 1.</p>

          <strong>Project Potential</strong>
          <p>The developed model generates patient-specific normal PET images and supports quantitative correction of physiological variability. Initial results demonstrate a significant reduction of SUV variance and improved detection of abnormal uptake patterns without requiring manually annotated training data.</p>
        </div>

        <div class="col-md-5 figure-column">
          {% include figure.liquid loading="eager" path="assets/img/Billede_projekt_15.1.jpg" title="Example image" class="img-fluid rounded z-depth-1" %}

          <div class="caption mt-3">
            <p><strong>Figure 1:</strong> Normal Twin PET pipeline. Personalized normal PET images are generated from CT and patient attributes and used for confounder correction and anomaly detection.</p>
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
              <strong>Location:</strong>
              <span>Department of Clinical Physiology and Nuclear Medicine, 3982</span>
            </div>
            <div class="contact-item">
              <strong>Position:</strong>
              <span>PhD Student</span>
            </div>

            <!-- Extra space between Position and Publications -->
            <div class="contact-item spacer"></div>

            <h4 class="small-header">Publications</h4>
            <div class="contact-item">
              <p><a class="publication-link" href="https://www.nature.com/articles/s41598-025-26827-y">Normal twin PET: personalized generative modeling for confounder correction and anomaly detection in whole-body PET/CT</a></p>
            </div>
          </div>
        </div>
      </div>
    </article>

    {% if page.related_publications %}
      <h2>References</h2>
      <div class="publications">
        {% bibliography --cited_in_order %}
      </div>
    {% endif %}

    {% if site.giscus and page.giscus_comments %}
      {% include giscus.liquid %}
    {% endif %}
  </div>
</div>
