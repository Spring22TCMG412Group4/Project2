---
layout: default 
---

## Welcome to the blog space! 

_Each team member will have a blog post on this page giving some info 
about them_ 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/Project2{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[back](./)
