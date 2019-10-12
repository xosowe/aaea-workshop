---
layout: default
---

# {{ site.title }}
<ul class="main-list">

{% for topic in site.topics %}
    <li>
        <h2>{{ topic.title }}</h2>
        <p>By {{ topic.author }}</p>
        {{ topic.headline }} - [Read more...]({{ topic.url }})
    </li>
{% endfor %}

    </ul>
