---
title: words
layout: default
section: words
---

# Katie's Blog

<ul id="posts">
{% for post in site.categories.words %}
  <li>
    <h3><a href="{{ post.url }}"> ({{post.date | date: "%b %d"}}) &mdash; {{ post.title }} </a></h3>
  </li>
{% endfor %}
</ol>
