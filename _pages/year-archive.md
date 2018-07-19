---
title: "Archived Posts"
layout: default
permalink: "year-archive/"
author_profile: true

---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
