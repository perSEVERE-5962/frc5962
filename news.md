---
title: News
hero-img-url: "/media/week0-finals-hang.jpg"
hero-title: News
---

<article class="posts" markdown="1">
{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %-d, %Y" }}*
{{ post.content }}
<!--<div class="post-data"> TAGS
{% if post.tags %}{% for tag in post.tags %}<a class="tag" href="{{ tag | prepend:'/tags/' | prepend:site.url }}">{{ tag }}</a> {% endfor %}{% endif %}
</div>-->
<div class="divider"></div>
{% endfor %}
</article>

<!--
<aside class="one-third" markdown="1">
## Archive

{% assign postsByYearMonth = site.posts | group_by_exp:"post", "post.date | date: '%B %Y'"  %}
{% for yearMonth in postsByYearMonth %}
<b>{{ yearMonth.name }}</b>
<ul>
{% for post in yearMonth.items %}<li><a href="{{ post.url }}">{{ post.title }}</a></li>{% endfor %}
</ul>
{% endfor %}
</aside>
-->