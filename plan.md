---
title: Plan du site
---
# {{ page.title }}

<ul>
  <li>
    <a href="/memos/index.html">Page d'accueil</a>
  </li>
  <li>
    Fiches 
<ul>
  {% for fiche in site.fiches %}
    <li>
      <a href="/memos{{ fiche.url }}">{{ fiche.title }}</a>
    </li>
  {% endfor %}
</ul>
  </li>
  </ul>
