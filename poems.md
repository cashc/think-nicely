---
layout: default
title: Poetry
description: I like to write poems.
last_modified_at: 2021-05-07
---

{% for poem in site.poetry %}
  <div class="poem-content">
    {{ poem.content }}
  </div>
  <a href="{{ poem.url | relative_url }}">
    →
  </a>
  <div class="poem-break"></div>
{% endfor %}
