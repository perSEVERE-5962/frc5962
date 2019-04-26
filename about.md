---
title: About
hero-img-url: "/media/unh.jpg"
hero-title: We are Team 5962 <br>perSEVERE
story:
---

## Our Story



## Our Students

{% for student in site.students %}
**{{ student.name }}{% if student.grad-year %} '{{ student.grad-year | slice: 2, 2 }}{% endif %}**
<br>{% if student.role %}{{ student.role }}{% endif %}
{% endfor %}

## Our Mentors

{% assign ordered_mentors = site.mentors | sort: "order_number" %}
{% for mentor in ordered_mentors %}
**{{ mentor.name }}**
<br>{% if mentor.role %}{{ mentor.role }}{% endif %}
{% endfor %}