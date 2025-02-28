---
layout: page
title: Beautifulsoup
permalink: /blog/categories/beautifulsoup/
---

<h5> Posts por Categoria : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.beautifulsoup %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>