---
title: "Les projets IF"
permalink : /projets/
pageurl : https://github.com/InfiniFab/infinifab.github.io/blob/master/projets.md
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
