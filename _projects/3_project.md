---
layout: default2
title: Deep Learning for Tumor Delineation on PET/CT of Head and Neck Cancer
description: PhD Project by David Kovacs
img: assets/img/P3.jpg
importance: 9
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
          <p>The project employs artificial intelligence to standardize tumor delineation on [<sup>18</sup>F]FDG-PET/CT images in patients with head and neck cancer (HNC). The aim is to reduce variability in this process to achieve more dependable results, potentially enhancing diagnosis and treatment. </p>

          <strong>Project Background</strong>
          <p>PET/CT with <sup>18</sup>F-FDG is integral to the oncologic evaluation of nodal involvement, identification of distant metastases, radiotherapy planning, response assessment, and patient follow-up. Overall, PET/CT plays a crucial role in the assessment of various cancer types, including HNC.<br>
          
          The project explores the application of Deep Learning for tumor delineation and automation of deriving biomarkers on HNC PET/CT images. These image biomarkers include a range of quantitative measurements or characteristics associated with tumor size, shape, and intensity. Through Deep Learning, these biomarkers can be generated with precision and efficiency.</p>

          <strong>Project Potential</strong>
          <p>By implementing Deep Learning to standardize tumor delineation on HNC PET/CT images, this project has potential in the field of radiation therapy and automating biomarker analysis. In radiation therapy, the implementation of Deep Learning will reduce clinical variability and lead to more uniform assessments within radiation therapy. Automating biomarker analysis simplifies a resource-intensive task, particularly when assessing tumor size and intensity in clinical or research settings.</p>
        </div>

        <div class="col-md-5 figure-column">
          {% include figure.liquid loading="eager" path="assets/img/Billede_projekt 3.jpg" title="Example image" class="img-fluid rounded z-depth-1" %}

          <div class="caption mt-3">
            <p><strong>Figure 1:</strong> Image in the axial plane of a 50-year-old man with head and neck cancer (HNC) of the rhinopharynx. Clinical scan delineated by an expert (blue) and by AI (green) with AI-to-expert agreement displayed in red.</p>
          </div>

          <div class="caption mt-3" style="text-align: left;">
            <p><strong>References:</strong> Kovacs, David G et al. “Clinical Evaluation of Deep Learning for Tumor Delineation on 18F-FDG PET/CT of Head and Neck Cancer.” Journal of nuclear medicine: official publication, Society of Nuclear Medicine, vol. 65,4 623–629. 22 Feb. 2024, doi:10.2967/jnumed.123.266574.</p>
          </div>


          <div class="custom-contact-box mt-4 border rounded shadow-sm">
            <h4 class="small-header">Contact Information</h4>
            <div class="contact-item">
              <strong>Name:</strong>
              <span>David Gergely Kovacs Petersen</span>
            </div>
            <div class="contact-item">
              <strong>Email:</strong>
              <span><a href="mailto:david.gergely.kovacs.petersen@regionh">david.gergely.kovacs.petersen@regionh.dk </a></span>
            </div>
            <div class="contact-item">
              <strong>Location:</strong>
              <span>Diagnostic Center, Center Management</span>
            </div>
            <div class="contact-item">
              <strong>Position:</strong>
              <span>PhD Student</span>
            </div>

            <!-- Extra space between Position and Publications -->
            <div class="contact-item spacer"></div>

            <h4 class="small-header">Publications</h4>
            <div class="contact-item">
              <p>
                <a class="publication-link" href="https://jnm.snmjournals.org/content/early/2024/02/22/jnumed.123.266574">Clinical Evaluation of Deep Learning for Tumor Delineation on 18F-FDG PET/CT of Head and Neck Cancer</a>
              </p>
              <p><strong>Data is shared as part of this project here: </strong>
                <a class="publication-link" href="https://rigshospitalet-tumour-segmentation.regionh.dk/">Rigshospitalet Tumor Segmentation</a>
              </p>
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


