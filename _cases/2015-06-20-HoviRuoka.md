---
title: HoviRuoka
date: 2015-06-20 00:00:00 Z
permalink: "/cases/HoviRuoka.html"
categories:
- Product
tags:
- Strategy
- Package
layout: case-template 
photo-thumb: HoviRuoka
---

<div class="main-column">
<h1>{{ page.title }}</h1>
<h3>{{ page.category }}</h3>
<br>
<p>
<strong>Hoviruoka</strong> is a small company based in Kouvola, Finland, producing ready to eat food products. The objective was to redesign the existing package into an experiential package that attracted and engaged with the user. 

The final solution was inspired by paper lunchbags. With a number of experiential touchpoints and design elements, our design was severely tested and the results were appreciated. an be attached to the head / arm and help the user direct the dog to pick correct objects from a clutter.
</p>
</div>

<div class="side-column">
<ul>
<h4> My role </h4>
<li>Product Strategy</li>
<li>Product Ownership</li>
<li>Product Development</li>
<li>Prototyping</li>
<li>User Testing</li>
<br>

<div class="gallery">
{% for image in site.static_files %}
{% assign pathname = "/images/work/HoviRuoka/" %}
{% if image.path contains pathname %}
<img src="{{ site.baseurl }}{{ image.path }}" alt="{{ page.title }} - image" class="gallery-item">
{% endif %}
{% endfor %}