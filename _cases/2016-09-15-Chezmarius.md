---
title: Chezmarius
date: 2016-09-15 00:00:00 Z
permalink: "/cases/Chezmarius.html"
categories:
- Design Research
tags:
- Strategy
- Research
layout: case-template 
photo: Chezmarius
---

<div class="main-column">
<h1>{{ page.title }}</h1>
<h3>{{ page.category }}</h3>
<br>
<p>
<strong>Chez Marius</strong> is a small brick and mortar shop located in downtown Helsinki. As part of a UX research project, our goal was to study the business and evaluate its services in relation to the customer experience and user satisfaction. For this, we gathered insights on the web services and the retail storefront through observation, interviews and surveys. 
</p>
</div>

<div class="side-column">
<ul>
<h4> My role </h4>
<li>User Research</li>
<li>Customer Journey</li>
<li>Personas</li>
<li>Service Experience</li>
<li>Stakeholder Analysis</li>
<li>Opportunity Identification</li>
<br>

<div class="gallery">
{% for image in site.static_files %}
{% assign pathname = "/images/work/Chezmarius/" %}
{% if image.path contains pathname %}
<img src="{{ site.baseurl }}{{ image.path }}" alt="{{ page.title }} - image" class="gallery-item">
{% endif %}
{% endfor %}