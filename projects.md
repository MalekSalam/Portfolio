---
layout: page
title: Projects
---

<h1>Projects</h1>

{% for project in site.projects %}
<div class="project-card">
  <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
  <img src="{{ project.image }}" alt="{{ project.title }}">
  <p>{{ project.excerpt }}</p>
</div>
{% endfor %}
