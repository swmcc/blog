---
layout: page
title: My Blog
tagline: 
---
I'm a software developer and mainly specialise in web applications, based in Glenavy, Northern Ireland.

## Posts

Here is a list of my posts.

<ul class="posts">
  {% for post in site.posts %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a> - <span>{{ post.date | date_to_string }}</span></li>
  {% endfor %}
</ul>


