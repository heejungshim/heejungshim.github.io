---
layout: page
title: software
permalink: /software/
description: Open-source statistical software and computational tools developed by the lab.
nav: true
nav_order: 4
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
  </div>
</div>
