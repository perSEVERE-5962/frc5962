---
title: About
hero-img-url: "/media/unh.jpg"
hero-title: We are Team 5962 <br>perSEVERE
story: Our story
---

## Our Story and Mission

<article markdown="1">
{{ page.story }}
</article>

<div class="divider"></div>

## Our Students

<article class="grid three-columns" markdown="1">
{% assign ordered-students = site.students | sort: "order-number" %}
{% for student in ordered-students %}
**{{ student.title }}{% if student.grad-year %} '{{ student.grad-year | slice: 2, 2 }}{% endif %}**
<br>{% if student.role %}{{ student.role }}{% endif %}
{% endfor %}
</article>


<div class="divider"></div>

## Our Mentors

<article class="grid two-columns" markdown="1">
{% assign ordered-mentors = site.mentors | sort: "order-number" %}
{% for mentor in ordered-mentors %}
**{{ mentor.title }}**
<br>{% if mentor.role %}{{ mentor.role }}{% endif %}
{% endfor %}
</article>