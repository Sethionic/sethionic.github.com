---
layout: page
title: Home
tagline: Efforts in Efficiency
---
{% include JB/setup %}

[About](about) [Projects](projects)

##Recent Posts:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

