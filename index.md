---
layout: default
---

# {{ site.title }}

{% for topic in site.topics %}
    <h2>{{ topic.title }}</h2>
    <br>By {{ topic.author }}
    {{ topic.headline }} - <a href="{{ topic.url }}"><em>Read more...</em></a>
{% endfor %}
