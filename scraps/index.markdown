---
title: scraps
layout: default
section: scraps
---

# Latest Scrapbooking Projects

<ul id="posts">
{% for post in site.categories.scraps %}
  <li>
    <h3><a href="{{ post.url }}"> {{ post.title }} </a></h3>
  </li>
{% endfor %}
</ol>
