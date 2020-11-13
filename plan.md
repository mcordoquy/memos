---
title: Plan
---
# {{ page.title }}

<ul>
  {% for fiche in site.fiches %}
    <li>
      <a href="{{ fiche.url }}">{{ fiche.title }}</a>
    </li>
  {% endfor %}
</ul>
