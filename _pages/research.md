---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
My research activities can be categorised into three main groups: hyperspectral image capture, computer vision algorithm development, and deep learning based computer vision models. This set of experiences allow me to provide bespoke solutions for image analysis-based problems and allows me to support research in a wide range of areas. Although my role is primarily in bioinformatics currently, I have experience in microbiology, civil engineering, aerospace and defence, and agritech sectors. 

My interests lie in creating algorithms and pipelines that start with understanding and manipulating data and end in the visulasation of the discovered results, as well as everything in between. 

Examples of my work can be seen by following the links below.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}