---
title: eats
layout: default
section: eats
---

# Our Favorite Recipes #
We will try to add a new recipe every day or two, at least until most of our favorite recipes are posted up here. We will also 
include our "Kitchen Experiments" (aka new recipes) along with all of the commentary -- and hilarity -- you'd expect from an experiment.

Also, we are working on a way to catagorize our recipes as "Appetizers," "Soups/Stews," "Main Courses," "Breads/Pastries," "Side Dishes," and "Desserts."
Please bear with us as we figure out how best to do this.
<ul id="posts">
{% for post in site.categories.eats %}
  <li>
    <h3><a href="{{ post.url }}"> {{ post.title }} </a></h3>
  </li>
{% endfor %}
</ol>
