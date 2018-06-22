---
layout: archive
title: ""
date: {{ date }}
permalink: /collections/
modified:
excerpt:
image:
  feature: archivo-viejo-con-las-cartas.jpg
  teaser:
  thumb:
---

<h5>Collection of Posts</h5>


<ul>

  {% for post in site.posts %}

​    <li>

​      <a href="{{ post.url }}">{{ post.title }}</a>

​    </li>

  {% endfor %}

</ul>



![Archivo Viejo]({{ "images/archivero.png" | absolute_url }})