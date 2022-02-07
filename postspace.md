---
layout: default 
---

## Welcome to our Blog! 

_Each team member will have a blog post on this page giving some info 
about them_ 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/Project2{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="/Project2{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

[back](/Project2)
