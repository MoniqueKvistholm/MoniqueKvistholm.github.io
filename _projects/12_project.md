---
layout: default2
title: Device-Less Data-Driven Cardiac and Respiratory Gating in PET Imaging
description: Project by Nanna Overbeck Petersen
img: assets/img/P12.jpg
importance: 1
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

  
  .video-container {
    display: flex;
    justify-content: center; /* Centrerer videoerne */
    align-items: flex-start;
    gap: 15px; /* Mindre afstand mellem videoerne */
    max-width: 100%;
    margin: auto;
  }

  .video-wrapper {
    display: flex;
    flex-direction: column; /* Bevarer video + tekst lodret */
    align-items: center;
    text-align: center;
    width: 40%; /* Sørger for, at begge videoer kan stå ved siden af hinanden */
  }

  .scaled-video {
    width: auto;
    height: 400px; /* Mindre højde, så de passer bedre */
    max-height: 100%;
    max-width: 100%;
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
          <p>Respiratory and cardiac motion during Positron Emission Tomography (PET) scans can cause image blurring, reducing diagnostic accuracy and affecting treatment planning. This project introduces a device-less, data-driven approach utilizing high-sensitivity long axial field-of-view (LAFOV) PET histo images. By enabling gated image reconstruction, the method improves image clarity, enhances tumor detectability, and delivers more reliable diagnostic information without the need for external devices.</p>
          <div style="height: 25px;"></div>

          <strong>Project Background</strong>
          <p>PET, often combined with Computed Tomography (CT), is a valuable tool for diagnosing and treatment planning in oncology, neurology, and cardiology. However, motion during PET scans can lead to reduced image quality, which may cause inaccurate measurements of tumor activity, size, and tumor visibility.</p>

          <p>Gated image reconstruction can help address these issues by segmenting scan data into phases of the motion cycle. Traditional gating methods rely on external devices, which increase preparation time and complexity.</p>

          <p>This project explores a device-less alternative using LAFOV [<sup>18</sup>F]FDG PET histo images and Short-Time Fourier Transform (STFT) analysis to estimate cardiac and respiratory motion. Results from 18 patients show that this method reliably matches reference measurements. Gated reconstructions demonstrated increased tumor maximum values (SUV<sub>max</sub>) and reduced tumor volume, improving tumor quantification and overall diagnostic precision.</p>
          <div style="height: 25px;"></div>


          <strong>Project Potential</strong>
          <p>This device-less, data-driven method has the potential to optimize PET imaging by reducing preparation time and eliminating the need for external devices. It enhances motion correction, leading to more accurate tumor measurements and improved diagnostic accuracy. LAFOV PET histo images have demonstrated consistent and reliable motion estimation, with gated reconstructions effectively isolating heart and lung motion. This approach improves image clarity and is particularly valuable for motion-sensitive cases, such as lung and cardiac imaging, offering potential for clinical integration.</p>
        
        <div style="height: 70px;"></div>

        <h5><strong>Gated PET Videos of Cardiac and Respiratory Motion</strong></h5>
        <div style="height: 20px;"></div>

        <figure>
          <div class="video-container">
            
            <!-- Video 1: Cardiac Motion -->
            <div class="video-wrapper">
              <video class="scaled-video" controls>
                <source src="https://moniquekvistholm.github.io/assets/video/cardiac_motion.mp4" type="video/mp4">
                Your browser does not support the video tag.
              </video>
              <figcaption class="figure-caption">Cardiac Motion</figcaption>
            </div>

            <!-- Video 2: Respiratory Motion -->
            <div class="video-wrapper">
              <video class="scaled-video" controls>
                <source src="https://moniquekvistholm.github.io/assets/video/respiratory_motion.mp4" type="video/mp4">
                Your browser does not support the video tag.
              </video>
              <figcaption class="figure-caption">Respiratory Motion</figcaption>
            </div>

          </div>

          <figcaption class="figure-caption" style="text-align: left; margin-top: 15px;">
            This example shows two gated PET videos. The left video illustrates a beating heart, created by combining individual gates into a continuous sequence. Similarly, the right video demonstrates respiratory motion, constructed from a series of respiratory-gated images. Both videos highlight how gating techniques capture and visualize motion during PET scans.
          </figcaption>
        </figure>




        </div>

        <div class="col-md-5 figure-column">
          <div class="image-box">
            <h5><strong><span style="color: #1E568E;">Approach:</span> Data-Driven gated PET reconstruction</strong></h5>

            <div style="height: 10px;"></div>
            <figure>
              <img src="{{ site.baseurl }}/assets/img/Billede_projekt_12.1.png" class="img-fluid" alt="Figure 1: Approach" />
              <div style="height: 15px;"></div>
              <figcaption class="figure-caption">
                <strong>Figure 1:</strong> Device-less, data-driven cardiac and respiratory gating using LAFOV PET histo images. PET scan data is divided into time-based segments called "gates." The dynamic signals for cardiac and respiratory motion are detected and analyzed, allowing each motion phase to be assigned to a gate. Over the 5-minute scan duration, these gates represent different points in the motion cycle. Images from each gate are reconstructed separately to create clearer, motion-corrected images. This method effectively reduces motion artifacts without the need for external devices.
              </figcaption>
            </figure>
            <div style="height: 30px;"></div>

            <h5><strong><span style="color: #1E568E;">Results:</span> Data-Driven gated PET reconstruction</strong></h5>
            <div style="height: 10px;"></div>
            <figure>
              <img src="{{ site.baseurl }}/assets/img/Billede_projekt_12.2.png" class="img-fluid" alt="Figure 2: Results" />
              <div style="height: 15px;"></div>
              <figcaption class="figure-caption"><strong>Figure 2</strong> displays eight respiratory-gated PET images (numbered 1 to 8), each representing different phases of the respiratory cycle. The image in the black box shows a standard 5-minute non-gated reconstruction. The black horizontal line indicates the top position of a lung tumor. In the gated series, the tumor position shifts across the different phases due to respiratory motion. In contrast, the non-gated image shows a more blurred and less defined tumor structure, highlighting the impact of motion correction in improving tumor localization and clarity.</figcaption>
            </figure>
          </div>
          <div style="height: 70px;"></div>
          
          <div class="custom-contact-box mt-6 border rounded shadow-sm">
            <h4 class="small-header">Contact Information</h4>
            <div class="contact-item">
                <strong>Name:</strong>
                <span>Nanna Overbeck Petersen</span>
            </div>
            <div class="contact-item">
                <strong>Email:</strong>
                <span><a href="mailto:nanna.overbeck.petersen.01@regionh.dk">nanna.overbeck.petersen.01@regionh.dk</a></span>
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
                <p><a class="publication-link" href="https://www.mdpi.com/2075-4418/14/18/2055">Device-Less Data-Driven Cardiac and Respiratory Gating Using LAFOV PET Histo Images</a></p>
            </div>
          </div>
        </div>
      </div>
    </article>
  </div>
</div>