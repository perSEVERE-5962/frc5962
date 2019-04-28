---
title: News
hero-img-url: "/media/unh.jpg"
hero-title: News
---

<article class="grid three-columns">

<article class="posts" markdown="1" style="grid-column: 1 / 3">
{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %-d, %Y" }}*
{{ post.content }}
<div class="post-data">
{% if post.tags %}{% for tag in post.tags %}<a class="tag" href="{{ tag | prepend:'/tags/' | prepend:site.url }}">{{ tag }}</a> {% endfor %}{% endif %}
</div>
<div class="divider"></div>
{% endfor %}
</article>

<aside markdown="1" style="grid-column: 3">
## Tags
<ul markdown="1">
{% for tag in site.tags %}
<li><a href="{{ tag[0] | prepend: '/tags/' | prepend: site.url }}">{{ tag[0] }}</a></li>
{% endfor %}
</ul>
</aside>

</article>