---
title: Welcome!
layout: base.njk
---

## Written versions of the Food Tech Life YouTube recipe videos

Hey, thanks for stopping by! 
I've recently moved the website and I'm in the process of re-doing the recipe pages.

More will be added as soon as I'm able to. If you need something specific let me know on [Twitter](https://twitter.com/AnotherDK)
Cheers

{% for page in collections.pages %}
- [{{ page.data.title }}]({{ page.url }})
{%- endfor %}