---
title: "Les projets IF"
permalink : /projets/
---

L'essence d'un fablab est de produire une multitude projet, et bien sur de les parager pour permettre aux personnes qui le souhaitent de reproduire ces projets



<!-- <ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
 -->

{% for post in site.posts %}
{% if post.tag == "projet" %}
 
 
|------------------------------------+---------------------|
|                 |                     | 
|------------------------------------|:-------------------:|
| [![]({{post.image}})]({{ post.url }}) | {{post.description}}|
|------------------------------------+---------------------|
 
{% endif %}
{% endfor %}
