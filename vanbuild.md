---
layout: default
title: Van Build
description: Some photos from my van build
last_modified_at: 2021-05-07
---

{% for project in site.vanbuild %}
  - <a href="#{{ project.title }}">{{ project.title }}</a>
{% endfor %}

<hr style="margin: 100px 0;">

# Alpha
Lived in for 3 months starting in December 2019
<div class="row">
  <div class="col">
    <img src="/public/vanbuild/alpha.0.jpg" />
  </div>
  <div class="col">
    <img src="/public/vanbuild/alpha.1.jpg" />
  </div>
  <div class="col">
    <img src="/public/vanbuild/alpha.2.jpg" />
  </div>
  <div class="col">
    <img src="/public/vanbuild/alpha.3.jpg" />
  </div>
</div>

<hr style="margin: 100px 0;">

# Beta
June 2020
<div class="row">
  <div class="col">
    <img src="/public/vanbuild/beta.0.jpg" />
  </div>
</div>

<hr style="margin: 100px 0;">

# Finished
Probably never 😅


{% for project in site.vanbuild %}
  <hr style="margin: 100px 0;">
  <h1 id="{{ project.title }}">{{ project.title }}</h1>
  {{ project.content }}
{% endfor %}
