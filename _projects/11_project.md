---
layout: default2
title: Automatic Annotation of Danish Chest X-ray Reports
description: Project by Lea Marie Pehrson and Alice Schiavone
img: assets/img/P11.jpg
importance: 5
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
          <p>This project explores the use of Natural Language Processing (NLP) to automate the annotation of Danish chest X-ray reports. By leveraging Artificial Intelligence (AI) -driven techniques, it aims to extract structured labels from free-text radiology reports, reducing the need for time-consuming manual annotations. This automated process is a crucial step toward developing an image classifier for thoracic X-rays, enhancing diagnostic workflows and improving accessibility to high-quality labeled datasets in non-English clinical settings.</p>
          <div style="height: 30px;"></div>

          <strong>Project Background</strong>
          <p>Developing AI models for medical imaging requires large, well-annotated datasets. However, manual annotation by radiologists is both expensive and time-consuming. This challenge is especially significant in smaller languages such as Danish, where there are few tools available for the automated extraction of structured medical data.</p>

          <p>To address this, the project employs NLP techniques to extract structured labels from free-text X-ray reports. The approach consists of three key steps:</p>

          <div style="height: 10px;"></div>

          <span style="font-weight: bold; color: #4a4a4a;">Rule-Based Labeling (RegEx)</span>: A set of rules are used to identify key medical findings and their negations.

          <div style="height: 10px;"></div>

          <span style="font-weight: bold; color: #4a4a4a;">Machine Learning-Based Labeling (BERT)</span>: Several BERT-based models, including Danish medical BERT (MeDa-BERT) and XLM-RoBERTa, are fine-tuned to classify findings.

          <div style="height: 10px;"></div>

          <span style="font-weight: bold; color: #4a4a4a;">Comparison & Evaluation</span>: Rule-based and machine learning labeling approaches are compared to determine their effectiveness, accuracy, and resource requirements.

          <div style="height: 25px;"></div>

          <p>Through this comparison, the project aims to establish the most effective strategy for automating medical report annotation in Danish, providing a foundation for further AI-driven advancements in medical annotation.</p>
          <div style="height: 30px;"></div>

          <strong>Project Potential</strong>
          <p>The findings from this project have important implications for clinical AI development, especially in non-English medical settings. The key contributions include:</p>

          <ul>
            <li><span style="font-weight: bold; color: #4a4a4a;">Performance of NLP in Medical Danish: </span>The project demonstrated that Danish BERT-based models perform better than rule-based methods, particularly for identifying negative findings.</li>

            <div style="height: 10px;"></div>

            <li><span style="font-weight: bold; color: #4a4a4a;">Application Beyond Danish Radiology Reports: </span>These methods could also be applied to other medical datasets in non-English languages, promoting wider adoption of AI in healthcare.</li>

            <div style="height: 10px;"></div>

            <li><span style="font-weight: bold; color: #4a4a4a;">Comparison & Evaluation: </span>Rule-based and machine learning labeling approaches are compared to determine their effectiveness, accuracy, and resource requirements.</li>
          </ul>

          <p>Despite these achievements, certain challenges remain, particularly in handling variation within Danish medical terminology and the limited availability of publicly accessible datasets. Addressing these will be crucial for further model improvements and clinical integration.</p>
        </div>

        <div class="col-md-5 figure-column">
          <div class="image-box">
            <div style="height: 15px;"></div>
            <figure>
              <img src="{{ site.baseurl }}/assets/img/Billede_projekt_11.1.png" class="img-fluid" alt="Figure 1: Billede 1" />
              <div style="height: 10px;"></div>
              <figcaption class="figure-caption"><strong>Figure 1:</strong> Overview of the annotation workflow for Danish chest X-ray reports. The figure illustrates how chest X-ray reports are annotated using both a rule-based method (RegEx) and a machine learning approach (BERT). BERT models trained on rule-based labels and fine-tuned on expert-annotated data improve classification performance, particularly for negative mentions.
             </div>
             <div style="height: 30px;"></div>
            </figcaption>
            </figure>
            <figure>
            <img src="{{ site.baseurl }}/assets/img/Billede_projekt_11.2.png" class="img-fluid" alt="Figure 2: Billede 2" />
            <div style="height: 10px;"></div>
            <figcaption class="figure-caption">
              <strong>Figure 2:</strong> Macro F1 scores for different NLP models on the 
              <span style="font-weight: bold; color: #4a4a4a;">HL</span> test set, comparing positive, negative, and weighted F1 performance. 
              The table shows that <span style="font-weight: bold; color: #4a4a4a;">DanskBERT</span> achieves the highest overall weighted F1 score (0.778), while 
              <span style="font-weight: bold; color: #4a4a4a;">XLM</span> performs best for positive mentions (0.756). 
              Models trained specifically on Danish data generally outperform multilingual models, especially for negative findings, where 
              <span style="font-weight: bold; color: #4a4a4a;">DanskBERT</span> has the highest score (0.717).
            </figcaption>
            </figure>
          </div>
          <div class="custom-contact-box mt-6 border rounded shadow-sm">
            <h4 class="small-header">Contact Information</h4>
            <div class="contact-item">
                <strong>Name:</strong>
                <span>Lea Marie Pehrson</span>
            </div>
            <div class="contact-item">
                <strong>Email:</strong>
                <span><a href="mailto:lea.marie.pehrson@gmail.com">lea.marie.pehrson@gmail.com</a></span>
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
              <p><a class="publication-link" href="https://www.mdpi.com/2673-2688/6/2/37">Effective Machine Learning Techniques for Non-English Radiology Report Classification: A Danish Case Study</a></p>
            </div>
          </div>
        </div>
      </div>
    </article>

  </div>
</div>



