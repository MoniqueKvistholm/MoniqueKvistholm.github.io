---
layout: page2
permalink: /whoisDEPICT/
title: Who is DEPICT
nav: false
nav_order: 
---

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
}
.hero-section {
  display: flex;
  background-color: #9DC0D1;
  flex-wrap: wrap; /* For bedre mobilvisning */
}
.hero-image-container {
  flex: 1 1 100%;
  display: flex;
  justify-content: flex-start;
  overflow: hidden;
}
.hero-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.hero-content {
  flex: 1 1 100%;
  padding: 40px 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.hero-content-box {
  width: 100%;
  max-width: 800px;
  padding: 30px;
  background-color: #F0F0F0;
  border-radius: 10px;
  text-align: left;
}
.hero-content h1 {
  font-size: 2em;
  font-weight: bold;
  margin-bottom: 20px;
  color: #1F4A60;
}
.hero-content p {
  font-size: 1em;
  line-height: 1.5;
}
.section {
  width: 100%;
  padding: 40px 20px; /* Juster padding for bedre mobilvisning */
  margin: 20px 0;
  display: flex;
  justify-content: center;
  align-items: center;
  border: none;
}
.content {
  width: 100%;
  max-width: 1200px;
  padding: 20px;
  text-align: left;
  color: #000e16;
  border-radius: 10px;
}
.section-title {
  font-size: 2em;
  font-weight: bold;
  margin-bottom: 20px;
  text-align: left;
  color: #0c1d26;
}
.vision-list {
  list-style-type: none;
  padding: 0;
}
.vision-item {
  background-color: #EFFAFF;
  border-radius: 5px;
  margin-bottom: 10px;
  padding: 15px;
  font-size: 1em;
  font-weight: bold;
  line-height: 1.8;
}
.purpose-vision {
  font-size: 1.2em;
  line-height: 1.5;
  text-align: center;
  color: #113242;
  max-width: 950px;
  margin: 0 auto;
  font-weight: bold;
}
.about-us {
  background-color: #FFFFFF;
}
.vision {
  background-color: #B1A294;
}
.additional {
  background-color: #FFFFFF;
}
.additional-columns {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap; /* For bedre mobilvisning */
}
.clearfix {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap; /* For bedre mobilvisning */
  margin: 20px auto;
  max-width: 1200px;
  padding: 0 20px;
  box-sizing: border-box;
}
.column {
  flex: 1 1 100%;
  padding: 20px;
  background-color: #FFFFFF;
  border-radius: 10px;
  margin-bottom: 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.column h2 {
  font-size: 1.5em;
  font-weight: bold;
  color: #1f4a60;
  margin-bottom: 10px;
  text-align: center;
}
.column p {
  font-size: 1.2em;
  font-weight: bold;
  color: #1B4257;
  line-height: 1.6;
  text-align: center;
}
.column img {
  max-width: 100%;
  height: auto;
  display: block;
  border-radius: 0px;
}
.btn {
  display: inline-block;
  padding: 10px 20px;
  margin-top: 10px;
  font-size: 0.9em;
  font-weight: bold;
  color: #fff;
  background-color: #1F4A60;
  text-align: center;
  text-decoration: none;
  border-radius: 0px;
  transition: background-color 0.3s ease;
}
.btn:hover {
  background-color: #113242;
}

/* Media Queries for Responsive Design */
@media (min-width: 768px) {
  .hero-image-container, .hero-content {
    flex: 1 1 50%;
  }
  .column {
    flex: 1 1 48%;
    margin-right: 2%;
  }
  .column:last-child {
    margin-right: 0;
  }
}

@media (max-width: 767px) {
  .hero-image-container, .hero-content {
    flex: 1 1 100%;
  }
  .column {
    flex: 1 1 100%;
  }
  .hero-content-box {
    width: 100%;
  }
  .hero-content h1 {
    font-size: 1.8em;
  }
  .hero-content p {
    font-size: 0.9em;
  }
  .section-title {
    font-size: 1.8em;
  }
  .purpose-vision {
    font-size: 1em;
  }
  .column h2 {
    font-size: 1.2em;
  }
  .column p {
    font-size: 1em;
  }
}
</style>

<!-- Hero Section with Large Image and Text Overlay -->
<div class="hero-section">
  <div class="hero-image-container">
    <img src="/assets/img/Design3.jpg" alt="Illustrationsbillede" class="hero-image">
  </div>
  <div class="hero-content">
    <div class="hero-content-box">
      <h1>About DEPICT</h1>

      <p>DEPICT is a collaborative initiative between Clinical Physiology and Nuclear Medicine, and Radiology and Imaging at Rigshospitalet's Diagnostic Center, specializing in advanced medical imaging powered by artificial intelligence (AI). Our interdisciplinary team includes experts from physics, engineering, computer science, mathematics, radiography, bioanalysis, and medicine. Together, we lead multiple projects focusing on optimizing imaging techniques and enhancing diagnostic capabilities.</p>
      <p>Using AI, DEPICT automates complex analyses such as lesion segmentation and biomarker extraction, accelerating diagnostic processes and ensuring accurate clinical assessments. We innovate in image acquisition to enhance clarity and detail, aiming for diagnostic accuracy while keeping patient comfort a priority.</p>
      <p>DEPICT leads the way in AI-driven medical imaging, aiming to transform healthcare by blending advanced research with practical clinical applications. Through innovation and collaboration, we shape the future of medical imaging.</p>
    </div>
  </div>
</div>

<!-- About Us Section -->
<div class="section about-us">
  <div class="content">
    <p class="purpose-vision">DEPICT envisions leading the way in the application of artificial intelligence and medical imaging by developing, validating, and implementing advanced and cutting-edge methods. This enables us to offer tailored solutions that meet the individual needs of each patient. Through collaboration in an interdisciplinary team, we extract image information efficiently and with minimal impact on patients, contributing to better outcomes.</p>
  </div>
</div>

<!-- Vision Section -->
<div class="section vision">
  <div class="content">
    <h2 class="section-title">Our Vision</h2>
    <h5>We aspire to shape the future of medical imaging.</h5><br>
    <ul class="vision-list">
      <li class="vision-item">The future of medical imaging is the right scan at the right time, tailored to the patient’s needs.</li>
      <li class="vision-item">The future of medical imaging is supported by automatic tools that quickly and efficiently gather all necessary information, seamlessly integrated and applied for diagnostics and within clinical settings.</li>
      <li class="vision-item">The future of medical imaging is based on interdisciplinary collaboration, the latest scanner technology, medical image analysis and artificial intelligence.</li>
    </ul>
  </div>
</div>

<div class="clearfix">
  <div class="column">
    <p>We are actively engaged in exciting projects with students at every academic level, ranging from bachelor's to PhD.<br> 
Read more about our projects</p>
    <a href="/projects" class="btn" target="_blank">Projects</a>
  </div>
  <div class="column">
    <img src="/assets/img/Nanna.jpg" alt="Image Description">
  </div>
</div>
