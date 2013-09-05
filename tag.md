---
layout: default
title: Tag Page Test
---

{{ site.tags }}

#site.tags.pagination

{{ site.tags.pagination }}

---

{{ site.categories }}

#site.categories.update

{{ site.categories.update }}

<h2>TEST</h2>
<ul>
  {% for post in site.categories.update %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>