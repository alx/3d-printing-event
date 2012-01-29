---
layout: default
title: 3D Printing - Toulouse
---
{% include JB/setup %}

<section id="log">
  <h2>Historique</h2>
{% for post in site.posts %}
  <div class="row">
    <div class="span4">
      <h3>{{ post.title }}</h3>
      <p>{{ post.custom-date }}</p>
    </div>

    <div class="span12">
      {{ post.content }}
    </div>
  </div>
  <hr>
{% endfor %}
</section>
