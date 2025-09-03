---
layout: default2
title: Automatic Lesion Segmentation on MRI Scans of Patients with Multiple Sclerosis
description: PhD Project by Amalie Hindsholm
img: assets/img/P2.jpg
importance: 13
category: 2024
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
          <p>The purpose of the project is to improve Multiple sclerosis (MS) lesion segmentation accuracy by utilizing large, heterogeneous clinical datasets and Deep Learning technology. These large-scale datasets from clinical practice are used to develop decision-support models for radiologists in the context of MS, specifically for the segmentation of MS lesion on magnetic resonance imaging (MRI). The objective is the clinical deployment of this model, which requires high-performance and adaptability to new scanners.</p>

          <strong>Project Background</strong>
          <p>MS is a chronic autoimmune disease of the central nervous system (CNS), causing long-term functional impairment. The disease is characterized by inflammatory axonal demyelination, resulting in focal lesions in the grey and white matter of the CNS, which serve as important biomarkers for disease diagnosis, activity, and treatment response. As part of their disease management, patients routinely undergo repeated MRI scans, contributing to a considerable workload for radiologists.<br>
          While there are existing models for automatic lesion segmentation, only a few are currently utilized in clinical practice. The existing models are struggling with generalization to clinical datasets. This is where this project steps in by incorporating large, heterogeneous training datasets directly from the MS clinics for training and validating an MS lesion segmentation model. The outcome is a model that achieves high precision and robustness against data from scanners that were not previously encountered.</p>

          <strong>Project Potential</strong>
          <p>The project enables the practical use of MS lesion segmentation in clinics, enabling the model to handle the variation found in clinical practice. This has the potential to reduce the time spent reviewing routine MS MRI scans for radiologists in the clinic and enable quantification of lesion volume as a biomarker.</p>
        </div>

        <div class="col-md-5 figure-column">
          {% include figure.liquid loading="eager" path="assets/img/Billede_projekt_2.jpg" title="Example image" class="img-fluid rounded z-depth-1" %}

          <div class="caption mt-3">
            <p><strong>Figure 1:</strong> MRI images from seven patients, - from seven different scanners. Two delineations: lesions marked by segmentation model (blue), and a reference delineation marked by a radiologist (pink).</p>
          </div>

          <div class="custom-contact-box mt-4 border rounded shadow-sm">
            <h4 class="small-header">Contact Information</h4>
            <div class="contact-item">
              <strong>Name:</strong>
              <span>Amalie Monberg Hindsholm</span>
            </div>
            <div class="contact-item">
              <strong>Email:</strong>
              <span><a href="mailto:amalie.monberg.hindsholm@regionh.dk">amalie.monberg.hindsholm@regionh.dk</a></span>
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
              <p><a class="publication-link" href="https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2023.1177540/full">Scanner agnostic large-scale evaluation of MS lesion delineation tool for clinical MRI</a></p>
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
