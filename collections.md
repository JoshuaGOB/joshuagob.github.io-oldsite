---
layout: archive
title: ""
date: {{ date }}
permalink: /collections/
modified:
excerpt:
image:
  feature: 
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