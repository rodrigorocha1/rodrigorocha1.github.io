---
layout: default
title: Projetos Desenvolvidos
---

<h1>Projetos Desenvolvidos</h1>

<div class="card-container">
    {% for projeto in site.projects %}
    <div class="card" style="background-color: aqua; border: 2px solid blue; border-radius: 8px; margin: 20px; padding: 10px;">
      <a href="{{ projeto.url | relative_url }}">
        <h2>{{ projeto.title }}</h2>
        <p>{{ projeto.description }}</p>
      </a>
    </div>
    {% endfor %}
</div>
