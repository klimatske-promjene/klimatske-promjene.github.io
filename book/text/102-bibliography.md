{% comment %}
---
title: Literatura
type: bibliography
---
## Knjige

{% if bibliography | where: "type", "book" %}
{% bibliography --query @book @incollection %}
{% else %}
*Trenutno nema dostupnih knjiga.*
{% endif %}

## Znanstveni radovi

{% if bibliography | where: "type", "phdthesis" %}
{% bibliography --query @phdthesis %}
{% else %}
*Trenutno nema dostupnih znanstvenih radova.*
{% endif %}

## Stručna literatura

{% if bibliography | where: "type", "misc" %}
{% bibliography --query @misc %}
{% else %}
*Trenutno nema dostupne stručne literature.*
{% endif %}
