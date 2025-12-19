---
layout: post
title: a post with advanced image components
date: 2025-12-18 08:25:00
description: this is what advanced image components could look like
tags: 
categories:
thumbnail: assets/img/prof_pic.jpg
images:
  compare: true
  slider: true
---

This is an example post with advanced image components.

## Image Comparison Slider

This is a simple image comparison slider. It uses the [img-comparison-slider](https://img-comparison-slider.sneas.io/) library. Check the [examples page](https://img-comparison-slider.sneas.io/examples.html) for more information of what you can achieve with it.

<img-comparison-slider>
  {% include figure.liquid path="assets/img/prof_pic.jpg" class="img-fluid rounded z-depth-1" slot="first" %}
  {% include figure.liquid path="assets/img/prof_pic_color.png" class="img-fluid rounded z-depth-1" slot="second" %}
</img-comparison-slider>
