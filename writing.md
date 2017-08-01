---
layout: page
title: Writing
permalink: /writing/
---


<h2>Writing</h2>
<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">
      <h2>{{ post.title }}</h2>
    </a>
  </li>
{% endfor %}
</ul>