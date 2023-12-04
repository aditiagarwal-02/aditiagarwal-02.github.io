---
layout: page
title: Image-to-Image Deep Learning for Climate and Weather Modelling

# description: Identifying brick kilns across India and reducing manual annotation efforts using active learning by 30%.
img: assets/img/climate.jpg
# redirect: https://brick-kilns-detector.streamlit.app/
importance: 3
category: work
github: https://github.com/aditiagarwal-02/Climax_project_autoencoder
---

# Project Description

The global toll of seven million lives annually due to air pollution underscores the urgent need to address the significant contribution of Particulate Matter (PM2.5 and PM10). These airborne particles pose a critical threat to public health as they can be readily inhaled into the lungs. Various robust sensors have been built to measure the concentration of particulate matter at multiple locations. However, sensors are expensive, prone to error, and noisy. Another set of techniques involves the utilization of environmental parameters such as surface temperature, snow cover, soil moisture content, etc., for forecasting. Chemical transport models is one such technique that relies on physical non-linear equation systems for estimating PM concentrations. However, these models are highly complex and thus time-consuming. Through this project, we aim to develop data-driven approaches, particularly cutting-edge techniques such as Autoencoders for predicting Particulate Matter(PM) concentrations using environmental parameters. We also explore the utilization of partial or single input features for forecasting.


<!-- <big><b>Research Paper accepted at NeurIPS 2023 Workshop on Active Learning in the Real World,2023. Here's the published [version](https://drive.google.com/file/d/1feZUEhzxBBCxrD9e98_UFtD1Ygvbqjlj/view?usp=drive_link)</b></big> -->

- [View the Report](https://drive.google.com/file/d/1Zg8O5x6UYMO3UjyfoHE9e6yqc-S9_czG/view?usp=drive_link)
<!-- - [GitHub Repository](https://github.com/aditiagarwal-02/brick-kiln) -->

## Project Showcase

This section contains a few snippets from the primary research questions adressed in the project. The complete report can be found [here](https://drive.google.com/file/d/1Zg8O5x6UYMO3UjyfoHE9e6yqc-S9_czG/view?usp=drive_link).

<br>


<h4>Environmental Parameters to forecast PM concentrations</h4>

<!-- Row 1 -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Final Presentation_page-0007.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        <div class="caption">Utiliizng environmental paramters as input</div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Final Presentation_page-0009.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        <div class="caption">Output Particulate Matter(PM) concentrations</div>
    </div>
</div>

<h4>Research Questions</h4>

<br>

<h5>Can we train a MLP AutoEncoder which uses a single channel as input?</h5>



<!-- Row 2 -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Final Presentation_page-0011.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        <!-- <div class="caption">Caption for the third image.</div> -->
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Final Presentation_page-0013.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        <!-- <div class="caption">Caption for the fourth image.</div> -->
    </div>
</div>

<h5>Can we utilize a Convolutional Autoencoder which can take single as well as multiple input channels?</h5>


<!-- Row 3 -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Final Presentation_page-0014.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        <!-- <div class="caption">Caption for the third image.</div> -->
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Final Presentation_page-0015.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        <!-- <div class="caption">Caption for the fourth image.</div> -->
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Final Presentation_page-0016.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        <!-- <div class="caption">Caption for the fourth image.</div> -->
    </div>
</div>

<h5>Can we utilize UNet architecture across single and multiple channel inputs?</h5>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Final Presentation_page-0017.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        <!-- <div class="caption">Caption for the third image.</div> -->
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Final Presentation_page-0018.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        <!-- <div class="caption">Caption for the fourth image.</div> -->
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Final Presentation_page-0019.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        <!-- <div class="caption">Caption for the fourth image.</div> -->
    </div>
</div>

<h5>Can we use only a subset of the channels for training?</h5>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Final Presentation_page-0020.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        <!-- <div class="caption">Caption for the third image.</div> -->
    </div>
</div>

<!-- Row 4 -->
<!-- ... (similar structure for additional rows) -->



