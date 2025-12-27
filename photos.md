---
layout: page
title: Photos
---

<h1>Photos</h1>

{% for photo in site.photos %}
<div class="photo-card">
  <h3><a href="{{ photo.url }}">{{ photo.title }}</a></h3>
  <img src="{{ photo.image }}" alt="{{ photo.title }}">
  <p>{{ photo.excerpt }}</p>
</div>
{% endfor %}
