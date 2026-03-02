---
layout: page
title: Restricted Boltzman Machines
permalink: /blog/categories/restricted_boltzman_machines/
---

<h5> Posts por Categoria : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.restricted_boltzman_machines %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>