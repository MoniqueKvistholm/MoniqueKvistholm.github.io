---
layout: default2
title: Optimizing Tissue Section Thickness for AI-Based Cell Classification
description: Project by Ida Skovgaard Christiansen
img: assets/img/P16.jpg
importance: 1
category: 2026
related_publications: false
---

<style>
  body {
    background-color: #E6DED0;
    margin: 0;
    padding: 0;
  }

  .custom-container {
    background-color: #E6DED0;
    padding: 20px;
    margin: 0;
    margin-bottom: 40px;
  }

  .post-title {
    font-weight: bold;
    color: #062A40;
    text-align: left;
    font-size: 2.5em;
    margin-top: 10px;
    margin-bottom: 20px;
  }

  .custom-contact-box {
    background-color: #F4F0EB;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin-top: 50px !important;
    margin-bottom: 10px;
  }

  .custom-contact-box h4.small-header {
    color: #062A40;
    font-weight: bold;
    font-size: 1em;
    margin-bottom: 15px;
  }

  .custom-contact-box .contact-item {
    margin-bottom: 8px;
  }

  .custom-contact-box .contact-item strong {
    color: #555;
    font-size: 0.9em;
  }

  .custom-contact-box .contact-item span {
    color: #333;
    font-size: 0.9em;
  }

  .custom-contact-box .contact-item:last-of-type {
    margin-bottom: 12px;
  }

  .custom-contact-box .spacer {
    margin-bottom: 12px;
  }

  article {
    font-size: 1.1em;
    line-height: 1.6;
  }

  .figure-column {
    padding-right: 15px;
  }

  .small-link {
    font-size: 0.8em;
  }

  .publication-link::before {
    content: '•';
    color: #062A40;
    font-size: 1.2em;
    margin-right: 8px;
    vertical-align: middle;
  }

  .project-figure {
    width: 80%;
    margin-left: auto;
    margin-right: auto;
  }

  /* Responsive design */
  @media (max-width: 768px) {
    .post-title {
      font-size: 1.8em;
    }

    .custom-container {
      padding: 10px;
      margin: 0 10px;
    }

    .figure-column {
      padding-right: 0;
    }

    .row {
      display: block;
      margin: 0;
    }

    .col-md-7,
    .col-md-5 {
      width: 100%;
      padding: 0;
    }
  }

  @media (max-width: 480px) {
    .post-title {
      font-size: 1.5em;
    }

    .custom-contact-box h4.small-header {
      font-size: 0.9em;
      margin-bottom: 12px;
    }

    article {
      font-size: 1em;
    }

    .custom-container {
      padding: 0 10px;
    }

    .figure-column {
      padding-right: 0;
    }

    .row {
      display: block;
      margin: 0;
    }

    .col-md-7,
    .col-md-5 {
      width: 100%;
      padding: 0;
    }
  }

  /* ---------- DARK MODE ---------- */
  html[data-theme="dark"] body {
    background-color: #E6DED0 !important;
    color: var(--global-text-color) !important;
  }

  html[data-theme="dark"] .custom-container {
    background-color: #E6DED0 !important;
    color: #0f172a !important;
  }

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

  html[data-theme="dark"] .custom-contact-box {
    background-color: #F4F0EB !important;
    border-color: rgba(0, 0, 0, 0.15) !important;
    color: #0f172a !important;
  }

  html[data-theme="dark"] .custom-container a {
    color: #154360 !important;
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
        <!-- Left column: project text and contact information -->
        <div class="col-md-7">
          <strong>Introduction</strong>
          <p>
            Deep learning-based cell segmentation and classification seem
            destined to play a role in future histology. While recent advances
            have enabled accurate identification of individual cells in
            histological images, achieving pathologist-level performance
            remains challenging due to the variability between histological
            tissue sections.
          </p>

          <strong>Project Purpose</strong>
          <p>
            The project investigates a slide-by-slide human-in-the-loop
            approach, in which manually annotated cells from each new tissue
            section are temporarily added as training data before classifying
            the remaining cells. To identify the optimal conditions for
            accurate and efficient cell classification, six tissue section
            groups (Fig. 1), including five microsection thicknesses
            (2–10 μm) and tissue sections produced using an automated
            microtome (DS), were evaluated.
          </p>

          <strong>Results and Impact</strong>
          <p>
            The results demonstrated that tissue sections produced using an
            automated microtome (DS), followed by 2 μm tissue sections,
            achieved the highest classification accuracy while requiring
            fewer manually annotated training cells (Fig. 2). These findings
            support the development of more accurate and efficient AI-assisted
            digital pathology workflows.
          </p>

          

          <div class="custom-contact-box mt-4 border rounded shadow-sm">
            <h4 class="small-header">Contact Information</h4>

            <div class="contact-item">
              <strong>Name:</strong>
              <span>Ida Skovgaard Christiansen</span>
            </div>

            <div class="contact-item">
              <strong>Email:</strong>
              <span>
                <a href="mailto:ida.skovgaard.christiansen@regionh.dk">
                  ida.skovgaard.christiansen@regionh.dk
                </a>
              </span>
            </div>

            <div class="contact-item">
              <strong>Location:</strong>
              <span>Department of Pathology, 5411</span>
            </div>

            <div class="contact-item">
              <strong>Position:</strong>
              <span>Pathologist</span>
            </div>

            <div class="contact-item spacer"></div>

            <h4 class="small-header">Publications</h4>

            <div class="contact-item">
              <p>
                <a
                  class="publication-link"
                  href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12059316/"
                >
                  Technical note: Impact of tissue section thickness on
                  accuracy of cell classification with a deep learning network
                </a>
              </p>
            </div>
          </div>
        </div>

        <!-- Right column: figures -->
        <div class="col-md-5 figure-column">
          <div class="project-figure">
            {% include figure.liquid
              loading="eager"
              path="assets/img/Billede_projekt_16.1.jpg"
              title="Figure 1"
              class="img-fluid rounded z-depth-1"
            %}

            <div class="caption mt-3">
              <p>
                <strong>Figure 1:</strong> Representative image tiles from the
                six tissue section groups evaluated in the study.
              </p>
            </div>
          </div>

          <div class="project-figure mt-4">
            {% include figure.liquid
              loading="lazy"
              path="assets/img/Billede_projekt_16.2.jpg"
              title="Figure 2"
              class="img-fluid rounded z-depth-1"
            %}

            <div class="caption mt-3">
              <p>
                <strong>Figure 2:</strong> Classification performance of the
                deep learning model across the six tissue section groups.
                Tissue sections produced with an automated microtome (DS)
                achieved the highest classification accuracy, followed by
                2 μm tissue sections.
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