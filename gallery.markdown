---
layout: gallery
title: "Gallery"
---


{% for image in site.data.gallery.images %}
  <div class="slide">
    <img src="{{ image.url }}" loading="lazy" alt="{{ image.alt }}">
  </div>
{% endfor %}