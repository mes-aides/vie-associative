---
permalink: /
layout: home
---

## À propos

L'association _Mes Aides_ pour but de lutter contre [l'asymétrie d'information](https://fr.wikipedia.org/wiki/Asym%C3%A9trie_d'information) vis à vis des règles qui régissent la vie des individus.

Pour cela, l’association met notamment à disposition un [simulateur d'aides](https://mes-aides.org/?utm_source=site_asso) à destination des particuliers et des personnes qui les accompagnent.

## Documents

- [Les statuts](statuts)
- [Le réglement intérieur](reglement)

## Assemblées générales

<ul>
{% for ag in site.assemblees-generales %}
  <li><a href="{{ ag.url | relative_url }}">{{ag.title}}</a></li>
{% endfor %}
<ul>
