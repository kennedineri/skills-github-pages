---
layout: default
title: Projects
permalink: /blog/
---

<h1>Project Blog</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date: "%B %d, %Y" }})
    </li>
  {% endfor %}
</ul>
