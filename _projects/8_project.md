---
layout: default2
title: Automated Brown Adipose Tissue Segmentation in CT Images of Lymphoma Patients
description: Project by Kasper Jørgensen
img: assets/img/P8.jpg
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

  .small-text {
  font-size: 0.8em; /* Juster efter behov for at gøre teksten mindre */
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
          <p>Brown adipose tissue (BAT) plays a crucial role in energy expenditure and thermoregulation, making it a key focus in metabolic disease research. This project investigates the use of a nnU-Net model for automated BAT segmentation in CT images of lymphoma patients. By relying solely on anatomical CT data, the approach avoids potential biases linked to metabolic activity in PET-based analyses.</p>
          <div style="height: 25px;"></div>

          <strong>Project Background</strong>
          <p>BAT segmentation often combines imaging modalities such as PET/CT or PET/MRI. However, PET-based segmentation reflects metabolic activity, which may obscure the anatomical boundaries of BAT. To address this, the project focuses on segmenting BAT using only CT data, independent of metabolic signals.</p>

          <p>Segmenting based solely on CT images is inherently challenging due to the minimal contrast between BAT and other adipose tissues. However, CT images still provide sufficient anatomical detail for physicians to identify BAT.</p>

          <p>Manual segmentation is time-consuming and prone to variability, generating the need for automated solutions. Deep learning methods like the nnU-Net model offer a powerful alternative by directly mapping image data to segmentation masks, eliminating the need for handcrafted features. In this project, we employ a 3D nnU-Net model trained exclusively on CT data to segment BAT. Integration into the TotalSegmentator software allows effective BAT segmentation without PET data. The model has been trained and tested on 189 CT images from lymphoma patients.</p>
          <div style="height: 25px;"></div>

          <strong>Project Potential</strong>
          <p>This automated BAT segmentation model represents a significant step forward in BAT analysis, enabling reliable automated segmentation directly from CT scans without the need for PET data. While the current test set is limited, further validation with larger and more diverse datasets could improve its robustness and broaden its clinical applicability. By making BAT analysis more efficient, this approach can contribute to advancing metabolic research and optimizing clinical workflows.</p>
        
        <div style="height: 70px;"></div>

        <h5><strong>Challenges Addressed by Automated CT-Based Segmentation</strong></h5>
        <div style="height: 20px;"></div>
        <figure>
          <img src="{{ site.baseurl }}/assets/img/Billede_projekt_8.3.png" class="img-fluid" alt="Figure 1: BAT Segmentation" style="width: 92%;" />  
        </figure>
        </div>

        <div class="col-md-5 figure-column">
          <div class="image-box">
            <h5><strong>Performance of the Automated BAT Segmentation Model</strong></h5>
            <div style="height: 15px;"></div>
            <figcaption class="figure-caption">The BAT segmentations predicted by the model were compared against the ground truth annotations (the manually marked regions of BAT) in CT images.
              <div style="height: 10px;"></div>
              <p>To evaluate the model's accuracy, an agreement analysis was performed. This analysis helps visually identify where the model's predictions align with or diverge from the ground truth annotations.</p>
            </figcaption>

            <div style="height: 10px;"></div>
            <figure>
              <img src="{{ site.baseurl }}/assets/img/Billede_projekt_8.1.png" class="img-fluid" alt="Figure 1: BAT Segmentation" />
              <div style="height: 15px;"></div>
              <figcaption class="figure-caption">
                <strong>Figure 1</strong> shows the BAT segmentation for four different test patients, comparing the original CT images, the manual ground truth annotations of BAT, the BAT segmentations predicted by the model, and the results of an agreement analysis.
                
                <div style="height: 10px;"></div>
                <p class="small-text"><strong>True Positive (Green):</strong> Correctly predicted BAT by the model.</p>
                <div style="height: 3px;"></div>
                <p class="small-text"><strong>False Negative (Red):</strong>BAT missed by the model that should have been identified.</p>
                <div style="height: 3px;"></div>
                <p class="small-text"><strong>False Positive (Blue):</strong> Areas incorrectly identified as BAT, where there is no BAT.</p>

                <div style="height: 15px;"></div>
                The model's performance is not perfect, and inconsistencies are observed in areas where the ground truth annotations are unclear or less precisely defined.
                <div style="height: 15px;"></div>
              </figcaption>
            </figure>
            <div style="height: 30px;"></div>

            <h5><strong>Performance of the Model Against CT/PET</strong></h5>
            <div style="height: 10px;"></div>
            <figure>
              <img src="{{ site.baseurl }}/assets/img/Billede_projekt_8.2.png" class="img-fluid" alt="Figure 2: Results of Low-Activity Scanning" />
              <div style="height: 15px;"></div>
              <figcaption class="figure-caption"><strong>Figur 2</strong> compares the predicted segmentations based solely on CT images with PET images for two patients with metabolically active BAT. The regions of increased PET activity align with the segmented BAT, suggesting that BAT can be accurately segmented using CT data alone, without the need for PET data.</figcaption>
            </figure>
          </div>
          <div style="height: 70px;"></div>
          
          <div class="custom-contact-box mt-6 border rounded shadow-sm">
            <h4 class="small-header">Contact Information</h4>
            <div class="contact-item">
                <strong>Name:</strong>
                <span>Kasper Jørgensen</span>
            </div>
            <div class="contact-item">
                <strong>Email:</strong>
                <span><a href="mailto:kasper.joergensen.02@regionh.dk">kasper.joergensen.02@regionh.dk</a></span>
            </div>
            <div class="contact-item">
                <strong>Location:</strong>
                <span>Department of Clinical Physiology and Nuclear Medicine, Rigshospitalet, Denmark</span>
            </div>
            <div class="contact-item">
                <strong>Position:</strong>
                <span>Student</span>
            </div>

            <!-- Extra space between Position and Publications -->
            <div class="contact-item spacer"></div>

            <h4 class="small-header">Publications</h4>
            <div class="contact-item">
                <p><a class="publication-link" href="https://www.mdpi.com/2075-4418/14/24/2786?fbclid=IwZXh0bgNhZW0CMTEAAR2sJTkYg2SEIfVbJFsOLqAGFGJt-8ZKpULtHksdvBmlRAx2wp1X_BKgogU_aem_gjyPLlNv_24MRiWhGvYfHA">Automated Supraclavicular Brown Adipose Tissue Segmentation in Computed Tomography Using nnU-Net: Integration with TotalSegmentator</a></p>
            </div>
             <div class="contact-item">
                <p><a class="publication-link" href="https://github.com/depict-rh/bat-seg">GitHub</a></p>
            </div>
          </div>
        </div>
      </div>
    </article>
  </div>
</div>