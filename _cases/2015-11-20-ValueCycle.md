---
title: ValueCycle
date: 2015-11-20 00:00:00 Z
permalink: "/cases/ValueCycle.html"
categories:
- Strategy
tags:
- Packaging
- Strategy
- ROI
- Tools
layout: case-template 
photo-thumb: ValueCycle
---

<div class="main-column">
<h1>{{ page.title }}</h1>
<h3>{{ page.category }}</h3>
<br>
<p>
The objective was to develop a PackageROI tool. It is used to evaluate package concepts and increase collaboration across their value networks. As a strategic tool it enables the business owner to consider all the elements of a package to plan, communicate and execute the development activities. It is a practical application of design thinking, giving a holistic perspective that integrates consumer desirability, technology feasibility and business viability. 
</p>
</div>

<div class="side-column">
<ul>
<h4> My role </h4>
<li>Strategist</li>
<li>Workshops</li>
<li>Case Studies</li>
<li>ROI analysis</li>
<li>Lifecycle development</li>
<li>Stakeholder Management</li>
<li>Systems Thinking</li>
<br>

<div class="gallery">
{% for image in site.static_files %}
{% assign pathname = "/images/work/ValueCycle/" %}
{% if image.path contains pathname %}
<img src="{{ site.baseurl }}{{ image.path }}" alt="{{ page.title }} - image" class="gallery-item">
{% endif %}
{% endfor %}