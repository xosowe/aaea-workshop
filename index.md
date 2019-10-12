---
layout: default
---

# {{ site.title }}
<ul class="main-list">

{% for topic in site.topics %}
    <li>
        <h2>{{ topic.title }}</h2>
        <p>By {{ topic.author }}</p>
    {{ topic.headline }} - <a href="{{ topic.url }}">Read more...</a>
    </li>
{% endfor %}

    </ul>
