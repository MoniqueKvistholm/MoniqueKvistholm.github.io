---
layout: page
title: Digital Twin for PET Scanning
description: PhD Project by Christian Hinge
img: assets/img/Billede_ projekt 1.jpg
importance: 1
category: work
related_publications: true
---

The aim of this project is to enhance the diagnostic potential of whole-body Positron Emission Tomography/Computed Tomography (PET/CT) imaging by creating personalized synthetic healthy PET baselines using advanced Deep Learning techniques.
Whole-body PET/CT imaging with FDG tracers is an invaluable diagnostic tool widely used in hospitals for detecting, diagnosing, and monitoring various diseases. However, standard analysis methods lack personalized healthy control images, reducing their precision and limiting the full diagnostic and prognostic potential of PET/CT imaging. This project addresses this limitation by introducing advanced Deep Learning techniques to synthesize personalized PET images based on the patient's own whole-body CT scans. This approach enables the development of images that reflect the individual patient's anatomical and physiological characteristics, increasing the accuracy of differentiating between normal and diseased states.
The project has the potential to detect deviations and subtle changes in organ uptake patterns by comparing the patient's digital twin with the actual PET scan. For example, in diabetes, a personalized healthy PET image can assess the disease by comparing it to the actual observed uptake. This project represents an innovative approach to improving diagnostic analysis methods, enhancing the accuracy of diagnoses, and increasing the effectiveness of treatment for individual patients.

    
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Billede_ projekt 1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1: Application of healthy PET for lymphoma detection. From left: CT, PET, sbPET: Synthetic healthy PET image, Abnormality: difference between PET and synthetic PET, Segmentation: identified cancerous areas.
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
