---
layout: page
title: Posts
tagline: 
---
<ul class='listing'>
  {% for post in site.posts %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a><span>{{ post.date | date_to_string }}</span></li>
  {% endfor %}
</ul>


