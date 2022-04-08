---
layout: page
title: "Projects"
permalink: /projects/
---

Here are all the projects featured on this website: 

<ul>
  {% for post in site.categories.basic %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>