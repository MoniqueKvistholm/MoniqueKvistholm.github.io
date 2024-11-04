---
layout: default2
title: Attenuation Correction in PET Scans Using Synthetic CT Images from the Emission Data
description: PhD Project by Maria Elkjær Montgomery
img: assets/img/P5.jpg
importance: 3
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
          <p>The project explores recent advancements in PET/CT scanning technology, specifically addressing the challenge of high radiation exposure from traditional CT scans. The primary focus is on utilizing artificial intelligence to generate synthetic CT images directly from PET scan data. By potentially replacing conventional CT scans, this approach aims to reduce patient radiation exposure while maintaining high image quality.</p>

          <strong>Project Background</strong>
          <p>Traditionally, PET scans require a separate CT scan for attenuation correction, leading to increased radiation exposure for the patients. This project presents a novel method using artificial intelligence to generate synthetic CT images directly from PET scans that have not undergone attenuation correction. By eliminating the need for a separate CT scan, this approach significantly reduces the overall radiation dose. The method involves a two-part system: a generator that produces synthetic CT images and a discriminator that assesses their authenticity. This setup enhances the quality of the synthetic images.</p>
          <p>Comparative studies between standard [^18F]FDG-PET images and synthetic PET images (sPET) revealed that in 30 out of 36 cases, the image quality was comparable, with only minor differences in six cases that were not clinically significant.</p>

          <strong>Project Potential</strong>
          <p>The results suggest that synthetic CT images generated with advanced algorithms are nearly as effective as traditional CT images. Additionally, synthetic PET images show minimal discrepancies compared to conventional PET scans. These findings indicate that the proposed model could be highly effective in clinical practice. This innovative approach holds potential for replacing CT scans in certain situations, thereby significantly reducing patient radiation exposure. This reduction is especially important for scenarios where minimizing radiation is critical, such as in children, pregnant women, or patients undergoing regular monitoring.</p>
        </div>

        <div class="col-md-5 figure-column">
          {% include figure.liquid loading="eager" path="assets/img/Billede_projekt 5.jpg" title="Example image" class="img-fluid rounded z-depth-1" %}

          <div class="caption mt-3">
            <p><strong>Figure 1:</strong>Representative patient scan using NAC PET from [15O]H2O for sCT synthesis.</p>
          </div>

          <div class="custom-contact-box mt-4 border rounded shadow-sm">
            <h4 class="small-header">Contact Information</h4>
            <div class="contact-item">
              <strong>Name:</strong>
              <span>Maria Elkjær Montgomery</span>
            </div>
            <div class="contact-item">
              <strong>Email:</strong>
              <span><a href="mailto:maria.elkjaer.montgomery@regionh.dk">maria.elkjaer.montgomery@regionh.dk</a></span>
            </div>
            <div class="contact-item">
              <strong>Location:</strong>
              <span>Department of Clinical Physiology and Nuclear Medicine, 3982</span>
              <span>Copenhagen University Hospital, 2100 København, Denmark</span>
            </div>
            <div class="contact-item">
              <strong>Position:</strong>
              <span>PhD Student</span>
            </div>

            <!-- Extra space between Position and Publications -->
            <div class="contact-item spacer"></div>

            <h4 class="small-header">Publications</h4>
            <div class="contact-item">
              <p><a class="publication-link" href="https://www.mdpi.com/2075-4418/13/24/3661">Attenuation Correction of Long Axial Field-of-View Positron Emission Tomography Using Synthetic Computed Tomography Derived from the Emission Data: Application to Low-Count Studies and Multiple Tracers</a></p>
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
