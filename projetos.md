---
layout: default
title: Projetos
---


## Bemvindo
<h1>Projetos Desenvolvidos</h1>

<div class="card-container">
    {% for projeto in site.projects %}
    <div class="card">
      <a href="{{ projeto.url | relative_url }}">
        <h2>{{ projeto.title }}</h2>
        <p>{{ projeto.description }}</p>
      </a>
    </div>
    {% endfor %}
</div>
