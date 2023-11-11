---
layout: default
title: Ica
---

<ul>
{% for recipe in site.data.recipes %}
  <li>
    <a href="{{ recipe.url }}">
      {{ recipe.title }}
    </a>
  </li>
{% endfor %}
</ul>
