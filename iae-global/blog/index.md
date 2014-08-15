---
published: true
layout: blog

---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/IAE-Architecture/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>