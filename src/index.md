---
title: Jenna's 11ty Portfolio
layout: base.njk
---

## Core 2 Interaction Lab



{% for page in collections.pages %}
  - [{{ page.data.title }}]({{ page.url }})
{%- endfor %}