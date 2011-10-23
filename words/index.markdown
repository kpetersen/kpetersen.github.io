---
title: words
layout: default
section: words
---

Recent Blog Posts
------------

<ul id="posts">
{% for post in site.categories.words %}
  <li>
    <h3><a href="{{ post.url }}"> {{ post.title }} </a></h3>
  </li>
{% endfor %}
</ol>
