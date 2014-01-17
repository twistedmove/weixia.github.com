---
layout: page
title: 

---
{% include JB/setup %}

### Behavioral Signal Processing Reading Group @ SAIL, USC

Internal Google Group: [BSPRG](https://groups.google.com/forum/#!forum/bsprg)

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


