---
layout: page
title: Apache Spark
permalink: /blog/categories/apache_spark/
---

<h5> Posts por Categoria : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.apache_spark %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>