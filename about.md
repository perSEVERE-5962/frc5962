---
title: About
hero-img-url: "/media/nedcmp.jpg"
hero-title: We are Team 5962 <br>perSEVERE
layout: default-with-hero
---

## Our Story and Mission

In April 2015, a few engineers from Analog Devices approached Dracut High School to explore the possibility of starting an FRC team as part of the school's Robotics Club. Despite months of effort from many people, the school was, unfortunately, unable to support an FRC team.

Undeterred, 5 students and 4 mentors opened Team 5962 to anyone from the area, rather than only students at a single high school. We approached the University of Massachusetts Lowell, and the College of Engineering graciously offered the use of its Makerspace.

We broadened our recruiting efforts, and by kickoff day our rookie season, our team included 33 students from 8 towns and 8 schools, 12 mentors, and more than 30 sponsors. Since then, we've competed at local district and off-season events, New England District Championships, and the *FIRST* Championship in Detroit.

**Our mission is to foster a vibrant, fun, and collaborative environment that inspires students to explore STEM, solve problems, and develop 21st century skills. We've earned the Chairman's Award at the district and regional level for our dedication to spreading *FIRST* in our communities.**

With our parent organization, Merrimack Valley Robotics, we extend that mission to students K-12 in northeastern Massachusetts, southern New Hampshire, and beyond. For more information about our parent organization Merrimack valley Robotics please visit [mvrobtics.net](http://mvrobotics.net)
<div class="divider"></div>

## Our Home

We meet at the UMass Lowell Makerspace (Falmouth 102) a few times a week. This space has graciously offered to us by the Francis College of Engineering since 2016. We have access to 3D printers, laser cutters, power tools, laptops, mills, and CNCs.

<div class="divider"></div>

## Our Students

We have students from many different towns and schools from the Merrimack valley and Southern New Hampshire. We have students in both high school and middle school. They are all trained in both technical and non-technical skills including CAD, electronics, programming and business skills.
<article class="grid three-columns">
{% assign ordered-students = site.students | sort: "order-number" %}
{% for student in ordered-students %}
<p>
<b>{{ student.title }}{% if student.grad-year %} '{{ student.grad-year | slice: 2, 2 }}{% endif %}</b>
{% if student.role %}<br>{{ student.role }}{% endif %}
{% if student.school %}<br>{{ student.school }}{% endif %}
{% if student.image %}<br>
![]({{ student.image }})
{% endif %}
</p>
{% endfor %}
</article>

<div class="divider"></div>

## Our Mentors

Team mentors work for businesses in the area, are parents of team members, are students at UMASS Lowell where the team meets. The mentors are all volunteers, offering hundreds of hours (or more) of service each year to help the team out.
<article class="grid two-columns" markdown="1">
{% assign ordered-mentors = site.mentors | sort: "order-number" %}
{% for mentor in ordered-mentors %}
**{{ mentor.title }}**
<br>{% if mentor.role %}{{ mentor.role }}{% endif %}
{% endfor %}