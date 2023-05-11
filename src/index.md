---
title: Jenna's 11ty Portfolio
layout: base.njk
---

## Core 2 Interaction Lab

Hello, I am Jenna and these are the 3 projects that I've worked on this semester!

{% for page in collections.pages %}
  - [{{ page.data.title }}]({{ page.url }})
{%- endfor %}

Since creativity exists in such a nebulous sphere of human understanding, the only people qualified to delve into the intricacies of such an ineffable concept are those that make a living off creativity. In the video linked above, the creative mastermind behind some of the 20th century's most significant musical acts, Rick Rubin, sits down to discuss why he believes that creativity thrives best under restriction.