## Welcome

Welcome to my personal page!  
I'm Yeray Alonso; a developer working for [Steema Software](https://www.steema.com), living in Girona. More about me [here](about.md).

## Here my blog posts

<hr>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
