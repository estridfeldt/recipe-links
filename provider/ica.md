---
layout: default
title: Ica
tag-name: ica
---

<ul>
{% for recipe in site.data.recipes %}
  {% if recipe.tags contains page.tag-name %}
  <li>
    <a href="{{ recipe.url }}">
      {{ recipe.title }}
    </a>
  </li>
  {% endif %}
{% endfor %}
</ul>