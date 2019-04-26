---
title: About
hero-img-url: "/media/unh.jpg"
hero-title: We are Team 5962 <br>perSEVERE
story: Our story
---

## Our Story

<article markdown="1">
{{ page.story }}
</article>

## Our Students

<article class="grid three-columns" markdown="1">
{% for student in site.students %}
**{{ student.name }}{% if student.grad-year %} '{{ student.grad-year | slice: 2, 2 }}{% endif %}**
<br>{% if student.role %}{{ student.role }}{% endif %}
{% endfor %}
</article>

## Our Mentors

<article class="grid two-columns" markdown="1">
{% assign ordered_mentors = site.mentors | sort: "order_number" %}
{% for mentor in ordered_mentors %}
**{{ mentor.name }}**
<br>{% if mentor.role %}{{ mentor.role }}{% endif %}
{% endfor %}
</article>