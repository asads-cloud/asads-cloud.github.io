---
layout: page
title: Projects
permalink: /projects/
---

Below are selected projects across data engineering and cloud infrastructure.

<ul>
  {% assign sorted = site.projects | sort: "weight" %}
  {% for project in sorted %}
  <li>
    <a href="{{ project.url | relative_url }}"><strong>{{ project.title }}</strong></a>
    — {{ project.subtitle }}
  </li>
  {% endfor %}
</ul>
