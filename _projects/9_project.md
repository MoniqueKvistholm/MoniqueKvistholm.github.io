---
layout: default2
title: AI-Based Support System for Chest X-ray Report Annotation - Exploring Annotator Performance Across Experience Levels 
description: Project by Lea Marie Pehrson
img: assets/img/P9.jpg
importance: 3s
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

  /* Modal styles */
  .modal {
    display: none; /* Hidden by default */
    position: fixed;
    z-index: 1; /* Sit on top */
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.8); /* Background color with transparency */
    overflow: auto; /* Enable scrolling if needed */
    padding-top: 60px;
    text-align: center; /* Center the content */
  }

  .modal-content {
    margin: auto;
    display: inline-block;
    max-width: 90%; /* Ensure the image does not stretch too far */
    max-height: 80vh; /* Allow some vertical space for the caption */
  }

  .modal-image {
    max-width: 100%; /* Make sure the image takes up full width */
    height: auto; /* Maintain aspect ratio */
  }

  .modal-caption {
    color: #fff; /* White text color for the caption */
    font-size: 1.2em; /* Increase the size of the caption text */
    margin-top: 15px; /* Space between image and caption */
    line-height: 1.5; /* Adjust line height for better readability */
  }
S

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
          <p>The project is a preliminary step in the development of an AI-based support system for chest X-ray report annotation, leveraging input from both radiologists and non-radiologists with varying levels of experience as an alternative when radiologists are unavailable. For developing the system, a study was conducted to explore how these different annotators annotate 200 chest X-ray reports. The goal is to investigate the performance and agreement between different annotators in annotating chest X-ray text reports. The aim of the project is to investigate the performance and agreement between these annotators in annotating chest X-ray text reports.</p>
          <div style="height: 25px;"></div>

          <strong>Project Background</strong>
          <p>Chest X-rays (CXRs) are the most performed diagnostic image modality. Based on technological advancements, there has been increased interest in improving radiologists’ efficiency and accuracy, particularly through AI-based systems for annotating findings on CXRs. These systems require training and testing using labeled data.</p>

          <p>Ideally, CXR training data should be manually labeled, but this process is time-consuming and expensive. Therefore, systems for automatic extractions of labels from CXT text reports have been developed. These extracted labels are lined to the corresponding images, creating large labeled datasets at lower cost and time.</p>

          <p>This project investigates how varying levels of radiological experience impact reading comprehension and annotation performance on CXR text reports. The Matthews Correlation Coefficient (MCC) was used to assess annotator performance and compare accuracy against "gold standard" labels, which were annotated by experienced radiologists. Results show that more experienced radiologists perform better, as reflected in their higher MCC scores.</p>
          <div style="height: 25px;"></div>

          <strong>Project Potential</strong>
          <p>Automating the annotation af CXR data has significant potential. Artificial intelligence can streamline the process, reducing both time and cost by extracting labels from existing CXR text reports. The resulting annotated dataset can be used to train and validate deep learning models to assist non-radiologists in their work.</p>
        
        <div style="height: 20px;"></div>

        <h5><strong>Conceptual Overview of the Chest X-ray Text Report Annotation Process</strong></h5>
        <div style="height: 20px;"></div>
        <figure>
          <img src="{{ site.baseurl }}/assets/img/Billede_projekt_9.1.png" class="img-fluid" id="image1" alt="Figure 1: Overview of the Chest X-ray" style="width: 94%;" />  
          <div style="height: 15px;"></div>
          <figcaption class="figure-caption">
                <strong>Figure 1:</strong> The process of annotating chest X-ray text reports for training an AI-based support system. 1. The chest X-ray report serves as the source of information for annotation. 2. Relevant data is extracted from the report to generate initial labels using a labeling hierarchy. 3. Human annotators (radiologists or non-radiologists) review the report and AI-generated labels, either confirming or modifying them. 4. The final annotations are compiled into a labeled dataset for training the deep learning model. 
              </figcaption>
        </figure>
        </div>

        <div class="col-md-5 figure-column">
          <div class="image-box">
            <h5><strong>Performance in Annotating Chest X-ray Reports</strong></h5>
            <div style="height: 15px;"></div>
            <figcaption class="figure-caption">This table shows the MCC values for various annotators, senior medical students, non-radiological physicians, novice radiographers, and experienced radiographers, when annotating chest X-ray reports. The values reflect the agreement between each group's annotations and the gold standard, created by experienced radiologists.
            </figcaption>

            <div style="height: 30px;"></div>
            <figure>
              <img src="{{ site.baseurl }}/assets/img/Billede_projekt_9.2.png" class="img-fluid" id="image2" alt="Figure 1: BAT Segmentation"/>
              <div style="height: 5px;"></div>
              <figcaption class="figure-caption">
                <strong>Table 1:</strong> Matthew’s correlation coefficients (MCC) for annotators’ performance in annotating chest X-ray text reports compared to gold standard annotation set for (a) positive findings and (b) negative findings.
                <div style="height: 15px;"></div>
                Across all annotators, the MCC values for negative findings were consistently higher than for positive findings, indicating a generally higher level of agreement with the gold standard for negative findings.
                <div style="height: 15px;"></div>
              </figcaption>
            </figure>
          </div>
          
          <div style="height: 20px;"></div>
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
                <span>Department of Radiology and Scanning, Rigshospitalet, Denmark</span>
            </div>
            <div class="contact-item">
                <strong>Position:</strong>
                <span>Student</span>
            </div>

            <!-- Extra space between Position and Publications -->
            <div class="contact-item spacer"></div>

            <h4 class="small-header">Publications</h4>
            <div class="contact-item">
                <p><a class="publication-link" href="https://marcofraccaro.github.io/download/publications/diagnostics-performance-agreement-when-annotating.pdf?fbclid=IwZXh0bgNhZW0CMTEAAR1YxkVf1mlRltxSV_1TSatfzfb23HNTLrt3-i1ZrXez1QrV5p8JnQyBXLg_aem_hnyDybsmxy1ncDgKOXi00w">Performance and Agreement When Annotating Chest X-ray Text Reports — A Preliminary Step in the Development of a Deep Learning-Based Prioritization and Detection System</a></p>
            </div>
          </div>
        </div>
      </div>
    </article>
  </div>
</div>

<!-- Modal Structure -->
<div id="myModal" class="modal">
  <span class="close" onclick="closeModal()">&times;</span>
  <div class="modal-content">
    <img class="modal-image" id="modalImage">
    <figcaption class="modal-caption"></figcaption> <!-- Her vises figurteksten -->
  </div>
</div>


<script>
  // Get the modal
  var modal = document.getElementById("myModal");

  // Get the image and insert it inside the modal
  var img1 = document.getElementById("image1");
  var img2 = document.getElementById("image2");
  var modalImg = document.getElementById("modalImage");
  var modalCaption = document.querySelector(".modal-caption"); // Access modal caption

  // When the user clicks on an image, open the modal and display the clicked image
  img1.onclick = function() {
    modal.style.display = "block";
    modalImg.src = img1.src; // Set the clicked image in the modal
    modalCaption.innerHTML = img1.nextElementSibling.innerHTML; // Copy the figcaption text
  }

  img2.onclick = function() {
    modal.style.display = "block";
    modalImg.src = img2.src; // Set the clicked image in the modal
    modalCaption.innerHTML = img2.nextElementSibling.innerHTML; // Copy the figcaption text
  }

  // When the user clicks on <span> (x), close the modal
  function closeModal() {
    modal.style.display = "none";
  }

  // Close the modal when the user clicks anywhere outside the modal image
  window.onclick = function(event) {
    if (event.target == modal) {
      modal.style.display = "none";
    }
  }
</script>