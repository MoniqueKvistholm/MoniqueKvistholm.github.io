---
layout: default2
title: Automatic Brain Tumor Segmentation
description: Project by Peter Jagd Sørensen
img: assets/img/P10.jpg
importance: 6
category: 2025
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
          <p>This project explores two key advancements in brain tumor segmentation. First, it repurposes the BraTS dataset, originally designed for preoperative analysis, by introducing a two-label annotation protocol tailored for postoperative scans. This adaptation enables deep learning (DL) algorithms to segment tumors more accurately on postoperative MRI scans by excluding resection cavities from tumor regions. Second, the project evaluates the performance of the state-of-the-art HD-GLIO algorithm, focusing on its ability to segment contrast-enhancing (CE) and non-enhancing (NE) lesions in an independent set of postoperative MRI scans.</p>
          <div style="height: 25px;"></div>

          <strong>Project Background</strong>
          <p>Automating brain tumor segmentation using DL algorithms has gained significant interest in recent years. The BraTS Challenge has been instrumental in this progress but is limited to preoperative MRI data, leaving a gap for postoperative scans. Most brain tumor patients undergo surgery, creating a need for annotated postoperative datasets, which are currently limited.</p>

          <p>From another perspective, the project aims to assess the performance of the HD-GLIO algorithm on an independent dataset of postoperative MRI scans. The study evaluates how well the algorithm segments two types of lesions: contrast-enhancing (CE) lesions and non-enhancing (NE) lesions, providing insight into its applicability for routine clinical workflows.</p>

          <p>By adapting the BraTS dataset with a two-label protocol, instead of a three-label protocol, and evaluating HD-GLIO, the project meets the gap between pre- and postoperative tumor segmentation, enabling DL algorithms to address real-world clinical needs.</p>


          <strong>Project Potential</strong>
          <p>The project has the potential to advance postoperative brain tumor segmentation by addressing the lack of annotated datasets with a novel two-label annotation protocol. This innovation enhances deep learning accuracy, improves disease monitoring, and supports personalized treatment. </p>

          <p>Although HD-GLIO shows strong potential for clinical use, particularly in segmenting larger tumors and NE lesions, it sometimes incorrectly identifies regions (see Figure 3). Addressing these challenges is key to refining models and ensuring clinical integration. This approach ultimately aims to streamline radiological workflows and improve patient outcomes.</p>
          

          <div style="height: 200px;"></div>
          
          <div class="custom-contact-box mt-6 border rounded shadow-sm">
            <h4 class="small-header">Contact Information</h4>
            <div class="contact-item">
                <strong>Name:</strong>
                <span>Peter Jagd Sørensen</span>
            </div>
            <div class="contact-item">
                <strong>Email:</strong>
                <span><a href="mailto:peter.jagd.soerensen@regionh.dk">peter.jagd.soerensen@regionh.dk</a></span>
            </div>
            <div class="contact-item">
                <strong>Location:</strong>
                <span>Department of Radiology and Scanning, Rigshospitalet</span>
            </div>
            <div class="contact-item">
                <strong>Position:</strong>
                <span>PhD Student</span>
            </div>

            <!-- Extra space between Position and Publications -->
            <div class="contact-item spacer"></div>

            <h4 class="small-header">Publications</h4>
            <div class="contact-item">
                <p><a class="publication-link" href="https://www.mdpi.com/2379-139X/10/9/105">Repurposing the Public BraTS Dataset for Postoperative Brain Tumour Treatment Response Monitoring</a></p>
            </div>
             <div class="contact-item">
                <p><a class="publication-link" href="https://www.mdpi.com/2075-4418/13/3/363">Evaluation of the HD-GLIO Deep Learning Algorithm for Brain Tumour Segmentation on Postoperative MRI</a></p>
            </div>
          </div>
        </div>

        <div class="col-md-5 figure-column">
          <div class="image-box">
            <div style="height: 15px;"></div>
            <figure>
              <img src="{{ site.baseurl }}/assets/img/Billede_projekt_10.1.png" class="img-fluid" alt="Figure 1: Billede 1" />
              <div style="height: 10px;"></div>
              <figcaption class="figure-caption"><strong>Figure 1</strong> compares three brain tumor segmentation methods: the three-label model (original BraTS protocol), the two-label model (postoperative adaptation), and the radiologist's ground truth. The figure highlights the effectiveness of the two-label protocol in excluding resection cavities, enhancing segmentation accuracy.
              <div style="height: 15px;"></div>
              <div style="font-size: smaller; line-height: 1.5;">
                    NCR+NET = necrosis, cysts and non-enhancing tumour core<br>
                    AT = active contrast-enhancing tumour<br>
                    ED = oedema and infiltrated tissue<br>
                    CE = contrast-enhancing tumour<br>
                    NE = non-enhancing hyperintense T2/FLAIR signal abnormalities.
             </div>
             <div style="height: 30px;"></div>
            </figcaption>
            </figure>
            <figure>
              <img src="{{ site.baseurl }}/assets/img/Billede_projekt_10.2.png" class="img-fluid" alt="Figure 2: Billede 2" />
              <div style="height: 10px;"></div>
              <figcaption class="figure-caption"><strong>Figure 2</strong> shows tumor segmentation accuracy using Dice similarity coefficients for three categories: contrast-enhancing tumors (CE), larger CE tumors (>1 cm³), and non-enhancing abnormalities (NE). The Two-label model shows higher accuracy for larger CE tumors, while both models vary in performance for smaller CE and NE regions.</figcaption>
            </figure>
            <div style="height: 30px;"></div>
            <figure>
              <img src="{{ site.baseurl }}/assets/img/Billede_projekt_10.3.jpg" class="img-fluid" alt="Figure 2: Billede 3" />
              <div style="height: 10px;"></div>
              <figcaption class="figure-caption"><strong>Figure 3</strong> illustrates an error in HD-GLIO's segmentation of CE tumor regions. The algorithm failed to capture part of the cavity wall identified as a CE tumor by the radiologist. Yellow highlights the radiologist's delineation, cyan shows HD-GLIO's segmentation, and green indicates overlap.</figcaption>
            </figure>
          </div>
        </div>
      </div>
    </article>

  </div>
</div>
