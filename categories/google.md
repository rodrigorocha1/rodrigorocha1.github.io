---
layout: page
title: Google
permalink: /blog/categories/google/
---

<h5> Posts por Categoria : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.google %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>