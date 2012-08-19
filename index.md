---
layout: page
title: Hello World!
tagline: How does this thing work?!1?
---
{% include JB/setup %}

Well, there's work to be done, but here's the posts:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


