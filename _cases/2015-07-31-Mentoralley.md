---
title: Mentoralley
date: 2015-07-31 00:00:00 Z
permalink: "/cases/Mentoralley.html"
categories:
- Digital Design
tags:
- Website
- Service
layout: case-template 
photo-thumb: Mentoralley
---

<div class="main-column">
<h1>{{ page.title }}</h1>
<h3>{{ page.category }}</h3>
<br>
<p>
<strong>Mentoralley</strong> is a startup that provides budding startups and innovators access to reputed mentors, advisors and investors around the world. Developed at the European Innovation Academy, our platform enabled the startups to reach out to the experts in the different parts of the world to develop, validate and market their ideas. Experts were motivated to participate as they gained access to new markets and had potential opportunities for new investments. My role was strategic and business development. 
</p>
</div>

<div class="side-column">
<ul>
<h4> My role </h4>
<li>Market Research</li>    
<li>Business Model</li>
<li>Prototyping</li>
<li>Moodboards</li>
<li>User testing</li>
<br>

<div class="gallery">
{% for image in site.static_files %}
{% assign pathname = "/images/work/Mentoralley/" %}
{% if image.path contains pathname %}
<img src="{{ site.baseurl }}{{ image.path }}" alt="{{ page.title }} - image" class="gallery-item">
{% endif %}
{% endfor %}