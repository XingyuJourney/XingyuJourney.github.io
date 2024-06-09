---
layout: base
title: "All history blogs"
---

<div class="blogs">
  <h1>Blogs</h1>
  <ul>
    {% assign reversed_posts = site.posts | reverse %}
    {% for post in reversed_posts%}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        <br>
        {% endfor %}
  </ul>
</div>
