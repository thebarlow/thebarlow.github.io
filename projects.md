---
layout: default
title: Projects
permalink: /projects/
---

# My Projects

<ul>
  {% for project in site.projects %}
    <li>
      <h2><a href="{{ project.link }}">{{ project.title }}</a></h2>
      <p>{{ project.description }}</p>
      <p>{{ project.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>