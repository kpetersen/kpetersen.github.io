---
title: eats
layout: default
section: eats
---

# Our Favorite Recipes
We will try to add a new recipe every day or two, at least until most of our favorite recipes are posted up here. We will also 
include our "Kitchen Experiments" (aka new recipes that turn out to be favorite dishes) along with all of the commentary -- and hilarity -- you'd expect from an experiment.

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
