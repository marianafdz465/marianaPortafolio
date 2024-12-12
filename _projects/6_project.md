---
layout: page
title: SC-COSMO
description: a project with no image
img: assets/img/SCCOSMO.png
importance: 4
category: work
---

The SC-COSMO modeling framework enables modeling of the epidemiology of COVID-19 for diverse populations and geographies. At its core, it is an age-structured, multi-compartment susceptible-exposed-infected-recovered (AS-MC-SEIR) model implemented in the R programming language. The model incorporates realistic demography and patterns of contacts sufficient for transmission. The model also incorporates non-pharmaceutical interventions (NPIs) (e.g., “social distancing”) timing and effects on reductions in contacts which may differ by demography. The model framework also allows for the comparison of many, future what-if scenarios and how they might impact outcomes over time and cumulatively (e.g., infections, cases, deaths, etc.). The framework can be implemented rapidly for specific populations and geographies based on generally available data from these places along with methods we have implemented to infer data elements that are unavailable (e.g., imputation and calibration).

    ---
   Read more aboput this
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SCCOSMO.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Model Framework
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
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
