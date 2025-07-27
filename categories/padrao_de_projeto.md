---
layout: page
title: Padrão de Projeto
permalink: /blog/categories/padrao_de_projeto/
---

<h5> Posts por Categoria : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.padrao_de_projeto %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>