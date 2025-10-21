---
layout: home
title: "Hi, I'm Asad"
---

<div align="center">
  <h1>Hi, I'm Asad ☁️⚡</h1>
  <p><strong>Cloud Data Engineer</strong> — I design, automate, and scale data platforms on AWS with Databricks, Spark, Airflow, and Terraform.</p>

  <p>
    <a href="/projects/" style="margin-right:10px;">View Projects</a>
    <a href="/about/">About</a>
  </p>
</div>

---

## Featured Work

<ul>
  {% assign featured = site.projects | where: "featured", true %}
  {% for project in featured %}
    <li>
      <a href="{{ project.url | relative_url }}"><strong>{{ project.title }}</strong></a>
      — {{ project.subtitle }}
    </li>
  {% endfor %}
</ul>
