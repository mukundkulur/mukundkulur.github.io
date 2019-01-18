---
title: Invalidiliitto
date: 2013-10-15 00:00:00 Z
permalink: "/cases/invalidiliitto.html"
categories:
- Design Research
tags:
- Product
- UX
layout: case-template 
photo: Invalidiliitto
---

<div class="main-column">
<h1>{{ page.title }}</h1>
<h3>{{ page.category }}</h3>
<br>
<p>
Collaborating with <strong>Invalidiliitto,</strong> The Finnish Association of People with Physical Disabilities, helped me gain insights on designing solutions for people with special needs. In this case it was to improve such a user and his/her interaction with dogs that assist them.
</p>
<p>
The dogs assisted the user in a variety of tasks - helping pick up things, open doors, etc. Based on insights obtained through shadowing, interviews and observation concepts were developed. The final solution is a dog friendly pointing device that can be attached to the head / arm and help the user direct the dog to pick correct objects from a clutter.
</p>
</div>

<div class="side-column">
<ul>
<h4> My role </h4>
<li>User Research</li>
<li>Shadowing</li>
<li>Personas</li>
<li>Moodboards</li>
<li>Concept Development</li>
<br>

<div class="gallery">
{% for image in site.static_files %}
{% assign pathname = "images/work/Invalidiliitto/" %}
{% if image.path contains pathname %}
<img src="{{ site.baseurl }}{{ image.path }}" alt="{{ page.title }} - image" class="gallery-item">
{% endif %}
{% endfor %}