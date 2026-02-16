---
layout: default2
title: Synthetic baseline for personalized PET analysis - Application in Alzheimer’s disease
description: Project by Christian Hinge
img: assets/img/P14.jpg
importance: 2
category: 2025
related_publications: false
---

<style>
  body {
    background-color: #EFF1F7; /* Background color for the entire page */
    margin: 0;
    padding: 0;
  }

  .custom-container {
    background-color: #EFF1F7; /* Background color for the content */
    padding: 20px; /* General padding */
    margin: 0; /* Remove margins */
    margin-bottom: 40px; /* Extra bottom margin for additional space */
  }

  .post-title {
    font-weight: bold;
    color:rgb(20, 23, 19); /* Color for the title */
    text-align: left; /* Left-align the title */
    font-size: 2.5em; /* Increase font size of the title */
    margin-top: 10px; /* Reduce top margin for the title */
    margin-bottom: 20px;
  }

  .custom-contact-box {
    background-color: #FFFFFF; /* Background color for the contact box */
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
    color: #000000; /* Color for the header in the contact box */
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
    color: #000000; /* Color of the bullet point */
    font-size: 1.2em; /* Size of the bullet point */
    margin-right: 8px; /* Space between the bullet point and the text */
    vertical-align: middle; /* Align bullet point with text */
  }

  /* New styles for the image box */
  .image-box {
    background-color: #FFFFFF; /* Background color for the image box */
    border: 1px solid #ddd; /* Border around the image box */
    border-radius: 5px; /* Rounded corners */
    padding: 20px; /* Padding inside the box */
    margin-top: 20px; /* Space above the image box */
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Shadow effect */
  }

  .image-box h3 {
    color: #000000; /* Color for the header in the image box */
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


  .col-md-7 {
    text-align: justify;      
    text-justify: inter-word; 
    padding-right: 60px;
  }

  /* Figurtekster */
  /* Figurtekster */
  .figure-caption {
    text-align: justify;
    text-justify: inter-word;
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

    <div style="height: 35px;"></div>

    <article>
      <div class="row">

        <!-- Venstre kolonne -->
        <div class="col-md-8">
          <strong>Introduction</strong>
          <p>Alzheimer's disease (AD) is often investigated using [<sup>18</sup>F]FDG-PET to assess cerebral glucose metabolism. However, current tools for uptake analysis rely on non-personalized templates, which poses a challenge since decreased glucose uptake could also reflect normal age-related changes, making it difficult to determine whether reduced glucose uptake is truly caused by AD or by other factors.</p>
          <div style="height: 25px;"></div>

          <strong>Project Background</strong>
          <p>To overcome this, the project proposes a deep learning approach that synthesizes personalized baselines for each patient based on their MR images. This synthetic baseline PET (sbPET) represents how the patient’s brain metabolism would look if it were healthy and it can serve as a hypothetical “healthy twin” reference image. By comparing the patient’s own [<sup>18</sup>F]FDG-PET images with the sbPET, the method produces abnormality maps that are more robust to anatomical variation.</p>
          <div style="height: 25px;"></div>

          <strong>Project Implementation</strong>
          <p>The results showed that the model reliably generated healthy-appearing PET images for cognitive normal (CN) subjects, and when applied to AD patients, the synthetic baselines enabled accurate detection of disease-related hypometabolism.</p>


          <div style="height: 40px;"></div>
          <figure style="text-align: center;">
            <img src="{{ site.baseurl }}/assets/img/Billede_projekt_14.1.jpg" class="img-fluid" id="image1" alt="Billede_projekt_14.1" style="width: 90%;" />
            <div style="height: 20px;"></div>
            <figcaption class="figure-caption">
              <strong>Figure 1.</strong> Average abnormality maps of 9 CN subjects and 10 AD patients. On average, the personalized method shows little to no abnormality for the CN group, while the AD group exhibits significant hypometabolism in the gray matter.
            </figcaption>
          </figure>
        </div><!-- /col-md-7 -->

        <!-- Højre kolonne -->
        <div class="col-md-4 figure-column">
          
          <div class="custom-contact-box mt-6 border rounded shadow-sm">
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
              <span>Department of Clinical Physiology and Nuclear Medicine, Rigshospitalet, Denmark</span>
            </div>
            <div class="contact-item">
              <strong>Position:</strong>
              <span>PhD Student</span>
            </div>

            <!-- Extra space between Position and Publications -->
            <div class="contact-item spacer"></div>

            <h4 class="small-header">Publications</h4>
            <div class="contact-item">
              <p><a class="publication-link" href="https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2022.1053783/full">A zero-dose synthetic baseline for the personalized analysis of [<sup>18</sup>F]FDG-PET: Application in Alzheimer’s disease</a></p>
            </div>
          </div><!-- /custom-contact-box -->
        </div><!-- /col-md-5 -->

      </div><!-- /row -->
    </article>

  </div><!-- /post -->
</div><!-- /custom-container -->
