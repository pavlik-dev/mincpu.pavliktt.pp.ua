---
layout: default
permalink: /news/
---

<h1>News</h1>

<div>
{% for post in site.posts %}
    {% include post.html post=post %}
{% endfor %}
</div>
