---
title: Jenna's 11ty Portfolio
layout: base.njk
---

## Core 2 Interaction Lab

Hello, I am Jenna and these are the 3 projects that I've worked on this semester!

{% for page in collections.pages %}
  - [{{ page.data.title }}]({{ page.url }})
{%- endfor %}