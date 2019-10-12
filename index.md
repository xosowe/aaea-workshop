---
layout: default
---

# {{ site.title }}
<ul class="main-list">

{% for page in site.pages %}
    <li>
        <h2>{{ page.title }}</h2>
        <p>By {{ page.author }}</p>
    {{ page.headline }} - <a href="{{ page.url }}">Read more...</a>
    </li>
{% endfor %}

    </ul>
