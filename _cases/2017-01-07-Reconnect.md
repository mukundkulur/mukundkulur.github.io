---
title: Reconnect
date: 2017-01-07 00:00:00 Z
permalink: "/cases/Reconnect.html"
categories:
- Innovation
tags:
- Strategy
- Innovation
layout: case-template 
photo-thumb: Reconnect
---

<div class="main-column">
<h1>{{ page.title }}</h1>
<h3>{{ page.category }}</h3>
<p>
<strong>Reconnect</strong> is a compilation on the future of public-private collaboration between Aalto University and Nokia. Gathering information on common interests, trends and developments from researchers, executives and board members across both organisations the final outcome provides recommendations to improve future collaborations. By backing our results with actual insights our recommendations was immediately approved by the board of both organisations.
</p>
<p>
My role has been to direct my team to obtain the insights across both organisations while keeping the overall objective in mind. Apart from that I also designed the report, the infographics and other content used in it.
</p>
</div>

<div class="side-column">
<ul>
<h4> My role </h4>
<li>Project Leader</li>
<li>Collaboration</li>
<li>Stakeholder Analysis</li>
<li>Forecasting </li>
<li>Infographics</li>
<li>Report Design</li>
<br>

<div class="gallery">
{% for image in site.static_files %}
{% assign pathname = "/images/work/Reconnect/" %}
{% if image.path contains pathname %}
<img src="{{ site.baseurl }}{{ image.path }}" alt="{{ page.title }} - image" class="gallery-item">
{% endif %}
{% endfor %}