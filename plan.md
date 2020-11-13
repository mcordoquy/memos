---
title: Plan
---
# {{ page.title }}

<ul>
  {% for page in site.pages %}
    <li>
      <a href="/memos{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
  {% for fiche in site.fiches %}
    <li>
      <a href="/memos{{ fiche.url }}">{{ fiche.title }}</a>
    </li>
  {% endfor %}
</ul>
