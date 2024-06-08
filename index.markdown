---
layout: custom_home
title: Welcome to My Custom Blog
---

# Welcome to My Custom Blog

This is a custom message for the homepage. You can add more content here as needed.

## Recent Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

## Photo Gallery

Here are some of my favorite photos:

<div class="photo-gallery">
  {% for photo in site.static_files %}
    {% if photo.path contains 'assets/images/photos' %}
      <div class="photo">
        <img src="{{ photo.path | relative_url }}" alt="{{ photo.name }}">
      </div>
    {% endif %}
  {% endfor %}
</div>
