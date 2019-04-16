---
layout: "default"
title: "News"
---

<div class="content-section content-section--whitebg" markdown="1">

{% for post in site.posts %}
<article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p><time>{{ post.date | date: '%a, %d.%m.%Y' }}</time></p>
    {{ post.excerpt }}
    <p><a class="content-link" href="{{ post.url }}">Read more</a></p>
</article>
{% endfor %}

</div>