---
layout: default
---
{% include JB/setup %}

<h1>Sobre</h1>

<p>vish mano</p>

<h1>Blog</h1>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
