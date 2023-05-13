---
title: Yeonwoo Lucy Kim 
layout: base.njk
---

## Projects


{% for project in collections.pages %}
  - [{{ project.data.title }}]({{ project.url }})
{%- endfor %}


