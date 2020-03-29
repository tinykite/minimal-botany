---
title: Minimal Botany
subtitle: A very silly website about plants.
layout: layouts/base.njk
---

<ul class="listing">
{%- for word in collections.words %}
  <li class="listing__item">
    {{ word.data.title }}
		{{ word.data.description }}
		{{ word.data.image }}
  </li>
{%- endfor%}
</ul>
