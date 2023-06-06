---
title: "Les ateliers IF"
permalink : /ateliers/
---

Fort d'une bonne experience acquise dans les fablabs, Infini Fab propose differents ateliers pour les fablabs voulant proposer une experience nouvelle à ses utilisateurs ou bien aux acteurs et lieux locaux voulant apporter de nouvelles perspectives, proposer une découverte des fablabs et de ce qu'on y fait.

Chaque ateliers proposé ci dessous vous fera découvrir le monde des fablabs ou bien explorer de nouveau domaine de ceux-ci en vous proposant la fabrication d'un objets fun et utile.


{% for post in site.posts %}
{% if post.tag == "atelier" %}
 - [{{ post.title }}]({{ post.url }})
{% endif %}
{% endfor %}