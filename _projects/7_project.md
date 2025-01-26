---
layout: default2
title: Feasibility of Multiparametric PET/MRI as a One-Stop Shop for RT Planning for Patients with HNC
description: Project by Anders Olin
img: assets/img/P7.jpg
importance: 4
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
    text-align: left; /* Ensure text inside the contact box is left-aligned */
    width: 100%; /* Ensure it fills the width of the column */
    max-width: 600px; /* Set a max-width to constrain the contact box */
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

  /* New styles for the image box */
  .image-box {
    background-color: #F4F0EB; /* Background color for the image box */
    border: 1px solid #ddd; /* Border around the image box */
    border-radius: 5px; /* Rounded corners */
    padding: 30px; /* Padding inside the box */
    margin-top: 20px; /* Space above the image box */
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Shadow effect */
  }

  .image-box h3 {
    color: #062A40; /* Color for the header in the image box */
    font-weight: bold; /* Make header bold */
    font-size: 1.5em; /* Smaller font size for the header */
  }

  .figure-caption {
    text-align: left; /* Left-align figure captions */
    font-size: 0.9em; /* Smaller font size for figure captions */
    margin-top: 5px; /* Space above figure captions */
    color: #000; /* Set caption color to black */
  }

  .figure-caption strong {
    font-weight: bold; /* Make 'Figur' text bold */
  }

  .img-fluid {
    max-width: 100%; /* Responsive images */
    height: auto; /* Maintain aspect ratio */
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
          <p>This project evaluates the feasibility of using combined positron emission tomography and magnetic resonance imaging (PET/MRI) for radiation therapy (RT) planning in head and neck cancer (HNC). By generating synthetic computed tomography (sCT) images from MRI data using deep learning, both tumor delineation and dose calculations can be achieved. This method improves precision, particularly in soft tissues like those in the head and neck, while also reducing radiation exposure.</p>
          <div style="height: 25px;"></div>

          <strong>Project Background</strong>
          <p>Head and neck cancer (HNC) includes various cancers in the head and neck regions, where precise tumor delineation is crucial due to the proximity of sensitive organs. Current RT planning for HNC relies on positron emission tomography (PET) for identification of lymph node involvement and computed tomography (CT) for calculating radiation doses. However, CT has limitations in accurately delineating soft tissues, which can lead to uncertainties in target definition and impact treatment outcomes. Replacing CT with MRI could therefore establish PET/MRI as the optimal imaging technique for RT planning.</p>

          <p>While MRI provides better soft tissue contrast, it lacks information about electron density, which is essential for accurate dose calculations. To address this limitation, a deep learning-based method has been developed to generate sCT images. The project aims to establish a PET/MRI scan protocol that enables PET/MRI as a comprehensive solution for RT planning by incorporating essential multiparametric MRI data and facilitating dose calculations through sCT.</p>
          <div style="height: 25px;"></div>

          <strong>Project Potential</strong>
          <p>The deep learning method developed for sCT generation has demonstrated clinical suitability for both PET attenuation correction and RT dose calculations, representing a significant advancement toward integrating multiparametric PET/MRI as a one-stop shop for RT planning. Notably, the model has undergone external validation using a dataset from Guy's and St. Thomas' Hospital in London, further confirming its robustness and generalizability across different sites. While the method does have limitations, such as the need for larger datasets and adjustments for specific cases, the sCT images have proven clinical suitable, achieving dose calculations with only 1% difference from reference CT. This close alignment highlights sCT’s potential for enhancing RT planning.</p>

          <div style="height: 70px;"></div>
          
          <div class="custom-figure-box mt-7" style="border: none; background: transparent;"> <!-- Removed border and made background transparent -->
          <h4 class="small-header">Model Performance with Metallic Dental Implants</h4>
          <div style="height: 25px;"></div>
          <div class="d-flex">
              <div class="figure-image" style="flex: 2; padding-right: 2px;"> <!-- Reduced flex size -->
                  <img src="/assets/img/Billede_projekt_7.2.jpg" alt="Cases illustrating the model's ability to handle metallic dental implants" class="img-fluid" style="max-width: 90%; height: auto;"/> <!-- Added max-width to control image size -->
              </div>
              <div class="figure-caption" style="flex: 2; padding-top: 20px;"> <!-- Kept padding for spacing -->
                  <p><strong>Figure 2.</strong> Cases illustrating the model's ability to handle metallic dental implants.</p>
                  <p>(A) A case from the external cohort, where the dental implant caused severe streaking artifacts in the computed tomography (CT) and a signal void in the magnetic resonance imaging without translating significantly into the synthetic CT.</p>
                  <p>(B-D) Cases from the local cohort, where dental implants only slightly affected the CT, but caused larger signal voids in the magnetic resonance images (MRI). For these cases the artifacts translated in varying degree into the synthetic CT images. Metal artifacts are marked on the MRI by red arrows.</p>
              </div>
          </div>
          </div>
        </div>

        <div class="col-md-5 figure-column">
          <div class="image-box">
            <h5>Comparison of the Two Dose Calculation Methods (CT and sCT)</h5>
            <div style="height: 15px;"></div>
            <figcaption class="figure-caption">The figure illustrates the comparison between computed tomography (CT) and synthetic CT (sCT) in the context of radiation therapy. </figcaption>
            <div style="height: 30px;"></div>
            <figure>
              <img src="{{ site.baseurl }}/assets/img/Billede_projekt_7.1.jpg" class="img-fluid" alt="Figure 1: Example of PET Imaging" />
              <div style="height: 20px;"></div>
              <figcaption class="figure-caption"><strong>Figure 1</strong> illustrates the results from a representative patient showing the CT based dose distribution (DoseCT), the synthetic CT (sCT) based dose distribution (DosesCT) and the voxel-wise relative dose difference between DosesCT and DoseCT (DDose). 
              <div style="height: 15px;"></div>
            </figcaption>
            </figure>
            <div style="height: 20px;"></div>
          </div>
          <div style="height: 150px;"></div>
          <div class="custom-contact-box mt-5 border rounded shadow-sm">
            <h4 class="small-header">Contact Information</h4>
            <div class="contact-item">
                <strong>Name:</strong>
                <span> Anders Olin</span>
            </div>
            <div class="contact-item">
                <strong>Email:</strong>
                <span><a href="mailto:?">mail</a></span>
            </div>
            <div class="contact-item">
                <strong>Location:</strong>
                <span>Department of Clinical Physiology and Nuclear Medicine</span>
            </div>
            <div class="contact-item">
                <strong>Position:</strong>
                <span>Student</span>
            </div>

            <!-- Extra space between Position and Publications -->
            <div class="contact-item spacer"></div>

            <h4 class="small-header">Publications</h4>
            <div class="contact-item">
                <p><a class="publication-link" href="https://www.redjournal.org/article/S0360-3016(20)31422-X/fulltext">Feasibility of Multiparametric Positron Emission Tomography/Magnetic Resonance Imaging as a One-Stop Shop for Radiation Therapy Planning for Patients with Head and Neck Cancer</a></p>
            </div>
            <div class="contact-item">
                <p><a class="publication-link" href="https://www.sciencedirect.com/science/article/pii/S2452109421001202">Robustness and Generalizability of Deep Learning Synthetic Computed Tomography for Positron Emission Tomography/Magnetic Resonance Imaging–Based Radiation Therapy Planning of Patients With Head and Neck Cancer</a></p>
            </div>
          </div>
        </div>
      </div>
    </article>

  </div>
</div>
