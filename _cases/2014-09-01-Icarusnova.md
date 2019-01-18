---
title: icarusnova
date: 2014-09-01 00:00:00 Z
permalink: "/cases/icarusnova.html"
categories:
- Product
tags:
- Product
- Management
- Strategy
layout: case-template 
photo: icarusnova
---

<div class="main-column">
<h1>{{ page.title }}</h1>
<h3>{{ page.category }}</h3>
<br>
<p>
I did my internship at <strong>Icarus Nova</strong>. Icarus was a product development firm, rebranding themselves to compete in the medical device and development sector. 

My work was to audit their design and development process for their Entraview Lean project, with a core focus on project planning, collaboration and execution. Using design methods and benchmarking, I analysed the operations and provided them results that enable them to better understand their processes and activities. 

In addition I worked in researching the market to identify possible business development opportunities. A short strategy for market penetration and customer development was proposed. 
</p>
</div>

<div class="side-column">
<ul>
<h4> My role </h4>
<li>Product Management</li>
<li>Project Audit</li>
<li>Stakeholder Analysis</li>
<li>Process Development</li>
<li>Market Research</li> 
<br>

<div class="gallery">
{% for image in site.static_files %}
{% assign pathname = "/images/work/Icarusnova/" %}
{% if image.path contains pathname %}
<img src="{{ site.baseurl }}{{ image.path }}" alt="{{ page.title }} - image" class="gallery-item">
{% endif %}
{% endfor %}