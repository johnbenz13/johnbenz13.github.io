---
layout: page
title: Disassemble the Web 
tagline: Disassemble the Web
---
{% include JB/setup %}

<ul>
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

