---
layout: default2
title: Clinical significance of combined density and texture analysis for stratifying the risk breast cancer in screening
description: PhD Project by Bolette Mikela Vilmun
img: assets/img/P4.jpg
importance: 12
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
          <p>The project focuses on the importance of incorporating mammographic density and tissue patterns in the development of personalized breast cancer screening programs. Mammographic dense breast tissue, which describes the proportions of connective and fatty tissue in the breast, increases the risk of developing breast cancer. Additionally, dense breast tissue can hide malignant changes. Furthermore, research indicates that other factors, such as patterns in breast tissue, may be associated with an increased risk of developing breast cancer. </p>

          <strong>Project Background</strong>
          <p>In Denmark, free mammography screening is offered to women aged 50-69 with the aim of detecting breast cancer early and improving treatment outcomes. However, mammography screening is far less effective for women with dense breast tissue, increasing the risk of being diagnosed with cancer between screenings and resulting in worse prognosis. There is a need for tailored screening programs that account for the varying risk.</p>
          <p>Therefore, it is crucial to have accurate risk stratification of women in screening. By combining information on tissue density, assessed with the Breast Imaging Reporting and Data System (BI-RADS) density score, with Deep Learning-based texture analysis, a more nuanced and precise risk assessment is achieved. This approach has the potential to identify woman at high-risk future breast cancer, who may benefit from more frequent and intensive screening examinations, while woman at lower risk may extend their screening intervals.</p>

          <strong>Project Potential</strong>
          <p>The project aims to enhance the understanding of how these two measurements can be utilized to identify women with different risk profiles for future breast cancer. The results have the potential to contribute to more effective screening strategies and better breast cancer prevention.</p>
        </div>

        <div class="col-md-5 figure-column">
          {% include figure.liquid loading="eager" path="assets/img/Billede_projekt 4.jpg " title="Example image" class="img-fluid rounded z-depth-1" %}

          <div class="caption mt-3">
            <p><strong>Figure 1:</strong> Four mammography screenings: Illustrates the variation in texture and density of breast tissue.</p>
          </div>

          <div class="custom-contact-box mt-4 border rounded shadow-sm">
            <h4 class="small-header">Contact Information</h4>
            <div class="contact-item">
              <strong>Name:</strong>
              <span>Bolette Mikela Vilmun </span>
            </div>
            <div class="contact-item">
              <strong>Email:</strong>
              <span><a href="mailto:bolette.mikela.vilmun@regionh.dk ">bolette.mikela.vilmun@regionh.dk
 </a></span>
            </div>
            <div class="contact-item">
              <strong>Location:</strong>
              <span>Department of Breast Imaging, Gentofte Hospital<br>Department of Radiology and Scanning, Rigshospitalet</span>
            </div>
            <div class="contact-item">
              <strong>Position:</strong>
              <span>PhD Student</span>
            </div>
            <div class="contact-item">
              <strong>Supervisors:</strong>
              <span>Michael Bachmann (Rigshospitalet), Ilse Vejborg (Gentofte Hospital)</span>
            </div>


            <!-- Extra space between Position and Publications -->
            <div class="contact-item spacer"></div>

            <h4 class="small-header">Publications</h4>
            <div class="contact-item">
              <p><a class="publication-link" href=""></a></p>
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


