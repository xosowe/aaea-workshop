---
layout: default
---

# {{ site.title }}

<ul>
  {% for topic in site.topics %}
    <li>
      <a href="{{ topic.url }}">{{ topic.title }}</a> - {{ topic.headline }}
      <br>By {{ topic.author }}
    </li>
  {% endfor %}
</ul>
