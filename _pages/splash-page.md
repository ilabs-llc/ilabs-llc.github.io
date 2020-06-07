---
title: "iLabs LLC"
layout: splash
permalink: /
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/appdev.svg

excerpt: "All about ideas, incubation, innovation and value delivery"
intro: 
  - excerpt: 'Welcome to iLabs LLC'
feature_row:
  - image_path: /assets/images/ideate.png
    alt: "Ideation"
    title: "Ideation"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."

  - image_path: /assets/images/incubate.png
    image_caption: "Incubation"
    alt: "Incubation"
    title: "Incubation"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
  
  - image_path: /assets/images/innovate.png
    title: "Innovation"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."

feature_row2:
  - image_path: /assets/images/ideate.png
    alt: "Ideation"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/incubate.png
    alt: "Incubation"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/innovate.png
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
