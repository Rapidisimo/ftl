---
title: Welcome!
layout: base.njk
---

## Welcome to this FTL test site 

I see you are interested in having the written form of the recipe. Click on the recipe you are looking for below. Cheers!

- Arepa de Choclo
- Easy Atol de Elote
- Falvorful Red Bean Soup
- Mexican Tostadas
- Pao de Quijo - GF Cheese Bread
- Pistachio and Cardamon Loaf
- Pulled Chicken Tacos with Avocado Crema
- Red Wine Sangria
- Refried Beans with Plantains

{% for page in collections.pages %}
- [{{ page.data.title }}]({{ page.url }})
{%- endfor %}