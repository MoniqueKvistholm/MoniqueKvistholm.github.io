---
layout: default2
title: Projects
permalink: /projects/
description:
nav: true
nav_order: 2
display_categories: [2024, 2023]
horizontal: false
---

<style>
  /* Tilpas baggrundsfarven her */
  body {
    background-color: #d9e6f2; /* Eksempel på en lys grå baggrundsfarve */
  }

  /* Ændre bredden af projektkasserne */
  .projects .col {
    flex: 0 0 calc(33.333% - 20px); /* 3 kolonner */
    max-width: calc(33.333% - 20px);
    margin: 10px;
  }

  @media (max-width: 992px) {
    .projects .col {
      flex: 0 0 calc(50% - 20px); /* 2 kolonner på mellemstore skærme */
      max-width: calc(50% - 20px);
    }
  }

  @media (max-width: 576px) {
    .projects .col {
      flex: 0 0 calc(100% - 20px); /* 1 kolonne på små skærme */
      max-width: calc(100% - 20px);
    }
  }

  /* Ensartet størrelse på billeder */
  .project-image {
    width: 100%;
    height: auto;
  }

  /* Justering af overskriftens placering */
  .project-title {
    margin-top: 0;
  }
</style>

<strong style="font-size: 1.5em;">DEPICT</strong> <span style="font-size: 1.2em;">consists of several projects based on artificial intelligence and medical image analysis. The projects work with imaging and automatic analysis, ensuring better and faster examinations and descriptions. Below, you can see examples of current projects.</span>

<!-- pages/projects.md -->
<div class="projects">
  {% if site.enable_project_categories and page.display_categories %}
    <!-- Display categorized projects -->
    {% for category in page.display_categories %}
      <a id="{{ category }}" href=".#{{ category }}">
        <h2 class="category">{{ category }}</h2>
      </a>
      {% assign categorized_projects = site.projects | where: "category", category %}
      {% assign sorted_projects = categorized_projects | sort: "importance" %}
      <!-- Generate cards for each project -->
      {% if page.horizontal %}
        <div class="container">
          <div class="row row-cols-1 row-cols-md-2">
            {% for project in sorted_projects %}
              {% include projects_horizontal.liquid %}
            {% endfor %}
          </div>
        </div>
      {% else %}
        <div class="row row-cols-1 row-cols-md-3">
          {% for project in sorted_projects %}
            {% include projects.liquid %}
          {% endfor %}
        </div>
      {% endif %}
    {% endfor %}

  {% else %}

    <!-- Display projects without categories -->
    {% assign sorted_projects = site.projects | sort: "importance" %}
    <!-- Generate cards for each project -->
    {% if page.horizontal %}
      <div class="container">
        <div class="row row-cols-1 row-cols-md-2">
          {% for project in sorted_projects %}
            {% include projects_horizontal.liquid %}
          {% endfor %}
        </div>
      </div>
    {% else %}
      <div class="row row-cols-1 row-cols-md-3">
        {% for project in sorted_projects %}
          {% include projects.liquid %}
        {% endfor %}
      </div>
    {% endif %}
  {% endif %}
</div>
