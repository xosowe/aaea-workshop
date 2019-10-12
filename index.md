---
layout: default
---

# {{ site.title }}
<ul class="main-list">
{% for page in site.pages %}
    <li>
        <h2>{{ page.title }}</h2> - {{ page.permalink }}
        <p>By {{ page.author }}</p>
    {{ page.headline }} - <a href="/{{ page.permalink }}">Read more...</a>
    </li>
{% endfor %}
</ul>
