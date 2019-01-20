---
layout: page
title: Work
permalink: /work/
---

This is the base Jekyll theme.

{% for work in site.work %}
  <h2>
    <a href="{{ work.url }}">{{ work.title }}</a>
  </h2>
{% endfor %}