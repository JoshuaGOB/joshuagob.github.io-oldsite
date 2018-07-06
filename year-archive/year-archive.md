---
title: "Archived Posts"
layout: archive-taxonomy
permalink: "/year-archive/"
author_profile: true

---

{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}