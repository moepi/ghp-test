---
layout: default
title: ghp test blog
---
<h1>{{ page.title }}</h1>

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>