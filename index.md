---
title: "Home"
---

## Welcome

Hello 👋🏼!  
My name is Yeray Alonso. If you want to know a few bits more about me, you can jump [here](about.md).

## Latest posts

<hr>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
