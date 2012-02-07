---
title: eats
layout: default
section: eats
---

# Our Favorite Recipes
This is a collection of our favorite recipes. Every dish posted here has been tested and thoroughly enjoyed by both Scott and Katie and their unsuspecting friends and family. We hope you'll find some favorite recipes in here, too! :)

*Note: We eat a lot of grilled meats and either steamed or sauteéd fresh vegetables, so the majority of things we eat aren't something I consider blog-worthy. I don't know what I would say. 
Perhaps something along the lines of, "Wash your head of broccoli, chop it up, put it in a rack over boiling water, steam for five minutes, eat." That doesn't really seem like a "recipe" so 
I don't include stuff like that. The same goes for the grilled or sauteéd meats we tend to eat. Anyway, my point is that we eat a lot more than the things listed here. I just pick and choose 
favorites that I think others might want to re-create when deciding what to post. 

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
