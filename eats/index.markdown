---
title: eats
layout: default
section: eats
---

# Favorite Recipes #

<ul id="posts">
{% for post in site.categories.eats %}
  <li>
    <h3><a href="{{ post.url }}"> {{ post.title }} </a></h3>
  </li>
{% endfor %}
</ol>
