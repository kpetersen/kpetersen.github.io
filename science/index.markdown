---
title: science
layout: default
---

# Scott's Projects

Usually Rocketry, Programming or Electronics - I'm the quintessential computer
nerd, so all my hobbies are equally nerdy :)

<ul id="posts">
{% for post in site.categories.science %}
  <li>
    <h3><a href="{{ post.url }}"> ({{post.date | date: "%b %d"}}) &mdash; {{ post.title }} </a></h3>
  </li>
{% endfor %}
</ol>