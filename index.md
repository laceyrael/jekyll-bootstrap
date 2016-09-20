---
layout: page
title: Good Books - Lacey Rael
tagline: Lacey shares book recommendations
---
{% include JB/setup %}

### Books:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

