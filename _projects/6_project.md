---
layout: default2
title: Deep Learning-Driven Improvements in Low-Activity PET Imaging for Neurodegenerative Diseases
description: Project by Raphaël Sura Daveau
img: assets/img/P6.jpg
importance: 10
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
    padding: 20px; /* Padding inside the box */
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
          <p>This project explores the enhancement of PET imaging for diagnosing neurodegenerative disorders such as Alzheimer's and Parkinson's by reducing the amount of radioactive material (activity) or scanning time while maintaining diagnostic accuracy. By developing a Deep Learning model for denoising (noise reduction), PET images with standard-activity quality can be obtained from low-activity scans, aiming to minimize radiation exposure and optimize the patient experience.</p>
          <div style="height: 25px;"></div>

          <strong>Project Background</strong>
          <p>Neurodegenerative disorders, including Alzheimer's disease (AD) and Parkinson's disease (PD), primarily affect patients over the age of 60. Alzheimer's disease is characterized by amyloid deposition in the brain and can be imaged using various PET radiotracers, including [<sup>11</sup>C]PiB, to confirm or rule out a clinical diagnosis. Similarly, specific PET tracers, such as [<sup>18</sup>F]FE-PE2I, can visualize the loss of dopaminergic neurons associated with Parkinson's disease, aiding in the diagnosis of patients.</p>

          <p>However, current PET scanning techniques face obstacles such as high radiation exposure and long scanning times. Low-activity PET images often result in reduced image quality, creating a need for improvements in scanning technologies and methods. This project addresses these challenges by utilizing a Deep Learning model for noise reduction, aimed at improving the image quality of low-dose PET scans. This enables reliable diagnostics with reduced radiation exposure and shorter scanning times.</p>

          <strong>Project Potential</strong>
          <p>The employed model has demonstrated its ability to effectively reduce noise in simulated low-activity PET images, resulting in images that closely match those obtained with full activity. This represents a significant improvement, enabling the potential to reduce tracer dose or scanning time in PET/CT without compromising image quality. This indicates the potential for implementing these methods in clinical practice, which may facilitate more effective strategies for diagnosing and treating neurodegenerative disorders.</p>

          <div style="height: 463px;"></div>
          
          <div class="custom-contact-box mt-6 border rounded shadow-sm">
            <h4 class="small-header">Contact Information</h4>
            <div class="contact-item">
                <strong>Name:</strong>
                <span>Raphaël Sura Daveau & Claes Nøhr Ladefoged</span>
            </div>
            <div class="contact-item">
                <strong>Email:</strong>
                <span><a href="mailto:claes.noehr.ladefoged@regionh.dk">claes.noehr.ladefoged@regionh.dk</a></span>
            </div>
            <div class="contact-item">
                <strong>Location:</strong>
                <span>Department of Clinical Physiology and Nuclear Medicine, Rigshospitalet, University of Copenhagen, Denmark</span>
            </div>
            <div class="contact-item">
                <strong>Position:</strong>
                <span>PhD Student</span>
            </div>

            <!-- Extra space between Position and Publications -->
            <div class="contact-item spacer"></div>

            <h4 class="small-header">Publications</h4>
            <div class="contact-item">
                <p><a class="publication-link" href="https://www.sciencedirect.com/science/article/pii/S1053811922005298#fig0001">Deep learning based low-activity PET reconstruction of [11C]PiB and [18F]FE-PE2I in neurodegenerative disorders</a></p>
            </div>
          </div>
        </div>

        <div class="col-md-5 figure-column">
          <div class="image-box">
            <h4>The Deep Learning Model for PET Image Denoising</h4>
            <div style="height: 15px;"></div>
            <figcaption class="figure-caption">The Deep Learning model is engineered to generate standard-activity PET images from low-activity PET scans. It utilizes a three-dimensional U-Net architecture, which consists of three primary components: an encoder, a bridge, and a decoder, working in unison to facilitate the denoising process.</figcaption>
            <div style="height: 30px;"></div>
            <figure>
              <img src="{{ site.baseurl }}/assets/img/Billede_projekt_6.1.jpg" class="img-fluid" alt="Figure 1: Example of PET Imaging" />
              <div style="height: 20px;"></div>
              <figcaption class="figure-caption"><strong>Figure 1</strong> illustrates the U-Net architecture employed to remove noise from low-activity PET images. The model takes two inputs: the low-activity PET image and a noise map that highlights the noise present in the image.
              <div style="height: 15px;"></div>
              The inputs are processed through several convolutional blocks, with average pooling applied after each block to manage image resolution (Avg pool) while leveraging multiple filters for feature extraction. Following processing at the lowest resolution (the bridge), the image undergoes upsampling (Trans Conv) through transposed convolution to restore clarity.
              <div style="height: 15px;"></div>
              To retain crucial information from earlier processing stages, features from the encoder are transferred to the decoder. Upon completion of the process, the model produces a new, denoised PET image, characterized by improved quality and reduced noise, derived from the original low-activity input. Improvements to low-activity PET images with the noise-reduced model are shown in Figure 2.
            </figcaption>
            </figure>
            <div style="height: 40px;"></div>
            <figure>
              <img src="{{ site.baseurl }}/assets/img/Billede_projekt_6.2.jpg" class="img-fluid" alt="Figure 2: Results of Low-Activity Scanning" />
              <div style="height: 20px;"></div>
              <figcaption class="figure-caption"><strong>Figure 2:</strong> PET images of the brain in the transverse plane using [<sup>11</sup>C]PiB (associated with AD) and [<sup>18</sup>F]FE-PE2I (associated with PD). The images show examples of normal, borderline, and abnormal scans. Each panel displays standard-activity images (left), low-activity images (center), and denoised images (right). White markings highlight areas of potential amyloid accumulation for [<sup>11</sup>C]PiB, relevant to Alzheimer's disease, and for [<sup>18</sup>F]FE-PE2I, where the putamen and caudate nucleus, associated with Parkinson’s disease, are highlighted. The model effectively cleanses the images of noise.</figcaption>
            </figure>
          </div>
        </div>
      </div>
    </article>

  </div>
</div>
