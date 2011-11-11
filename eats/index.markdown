---
title: eats
layout: default
section: eats
---

# Our Favorite Recipes
This is a collection of our favorite recipes. Every dish posted here has been tested and thoroughly enjoyed by both Scott and Katie. We hope you'll find some favorite recipes in here, too! :)

## Appetizers
{% for post in site.categories.appetizers %}
* ### [{{post.title}}]({{post.url}})
{% endfor %}

## Breads
{% for post in site.categories.breads %}
* ### [{{post.title}}]({{post.url}})
{% endfor %}

## Soups
{% for post in site.categories.soups %}
* ### [{{post.title}}]({{post.url}})
{% endfor %}

## Entrees
{% for post in site.categories.entrees %}
* ### [{{post.title}}]({{post.url}})
{% endfor %}

## Sides
{% for post in site.categories.sides %}
* ### [{{post.title}}]({{post.url}})
{% endfor %}

## Desserts
{% for post in site.categories.desserts %}
* ### [{{post.title}}]({{post.url}})
{% endfor %}
