---
layout: page
title: Research
permalink: /projects/
description: Selected peer-reviewed work from the curriculum vitae.
nav: true
nav_order: 3
---

<div class="research-list">
  <h2>Research interests</h2>
  <ul class="research-list__interests">
    <li>Tropical cyclones</li>
    <li>Predictability and internal variability of the climate</li>
    <li>Atmospheric water vapor</li>
    <li>Cloud feedback mechanisms</li>
    <li>Large-scale fluid dynamics</li>
    <li>Satellite-based observations of clouds</li>
    <li>Climate change</li>
    <li>Development of atmospheric numerical models</li>
  </ul>

  <h2>Selected research</h2>
  {% assign research_projects = site.projects | sort: "importance" %}
  {% for project in research_projects %}
    <article class="research-list__item">
      <h3><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h3>
      <p>{{ project.description }}</p>
    </article>
  {% endfor %}
</div>
