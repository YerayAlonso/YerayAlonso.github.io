---
title: "Home"
---

## Welcome

Welcome to my personal page!  
As you deduced from the url, my name is Yeray Alonso. If you want to know a few bits more about me, you can jump [here](about.md).

## Here the blog posts

<hr>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
