---
layout: page
title: Training Visual Language Models with Object Detection
description: Vision Language Models - Remote Sensing - Multimodality
img: assets/img/earth_obs.jpg
importance: 1
category: school
---

This work was written under the supervision of Syrielle Montariol, and was hosted by the NLP and ECEO labs at EPFL, Switzerland. This work was orally presented by Pr. Devis Tuia in IGARSS 2024, Athens. 

<a href="/assets/pdf/IGARSS_2024.pdf" style="display:inline-block;">
  <img src="/assets/img/pdf-icon.png" alt="Report PDF" width="30" height="30" style="filter: invert(0);">
</a>

# Abstract

Recently, Vision Language Models (VLMs) have shown
exceptional progress in tasks previously dominated by spe-
cialised computer vision models. This is increasingly the
case when visual grounding capabilities, such as the ability
to semantically understand or generate bounding boxes over
an input image, are required. 

However, how these capabilities transfer to specialized domains such as remote sens-
ing remains understudied, despite the recent multiplication
of specialised models for Earth observation. In this work,
we evaluate how grounding visual entities with clear text
bounding-box generations affect VLM performance in satel-
lite imagery. 

To this end, we create two instruction-following
tasks sourced from the xBD dataset, describing changes due
to natural disasters observed in satellite images. We fine-
tune several instances of MiniGPTv2, one of the few openly
available VLMs with grounding capabilities, on these tasks
and evaluate their performance under the “grounded”/“not
grounded” settings. We found that generating bounding
boxes to refer to visual entities does not necessarily increase
in-sample performance, but might decrease the generalization
gap when restrained to images with few entities.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/igarss_example.png" title="Model inference example" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
</div>