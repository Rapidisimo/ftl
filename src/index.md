---
title: Recipes and Blog Posts
layout: base.njk
---

Hi, thanks for stopping by!  
Below you can find the written version to some of my favorite recipes.  
  
  
{% for page in collections.recipes %}
- [{{ page.data.title }}]({{ page.url }})
{%- endfor %}