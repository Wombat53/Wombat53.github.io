---
layout: default
title: Blog
---

<h2>Seznam příspěvků</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%-d. %-m. %Y" }}
    </li>
  {% endfor %}
</ul>
