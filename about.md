---
title: About
hero-img-url: "/media/nedcmp.jpg"
hero-title: We are Team 5962 <br>perSEVERE
story: "<p>In April 2015, a few engineers from Analog Devices approached Dracut High
  School to explore the possibility of starting an FRC team as part of the school's
  Robotics Club. Despite months of effort from many people, the school was, unfortunately,
  unable to support an FRC team.</p> <p>Undeterred, 5 students and 4 mentors opened
  Team 5962 to anyone from the area, rather than only students at a single high school.
  We approached the University of Massachusetts Lowell, and the College of Engineering
  graciously offered the use of its Makerspace.</p> <p>We broadened our recruiting
  efforts, and by kickoff day our rookie season, our team included 33 students from
  8 towns and 8 schools, 12 mentors, and more than 30 sponsors. Since then, we've
  competed at local district and off-season events, New England District Championships,
  and the <i>FIRST</i> Championship in Detroit.</p> <p>Our mission is to foster a
  vibrant, fun, and collaborative environment that inspires students to explore STEM,
  solve problems, and develop 21st century skills. We've earned the Chairman's Award
  at the district and regional level for our dedication to spreading <i>FIRST</i>
  in our communities.</p> <p>With our parent organization, Merrimack Valley Robotics,
  we extend that mission to students K-12 in northeastern Massachusetts, southern
  New Hampshire, and beyond.</p>\n"
---

## Mission Statement
The mission of Merrimack Valley Robotics, Inc. and FRC Team 5962 is to promote growth of Science, Technology, Engineering, and Math (STEM) activities for students in kindergarten through 12th grade within the Merrimack Valley and surrounding areas of Massachusetts and Southern New Hampshire.


## Our Story and Mission

<article markdown="1">
{{ page.story }}
</article

<div class="divider"></div>


## Our Home
We meet at the UMass Lowell Makerspace, Falmouth 102 on Wednesday and Fridays 5-8 and Sunday 10-2.


This space is graciously offered to us by the UMass Lowell College of Engineering since 2016. We have access to 3d printers, Laser cutters, Power Tools, Laptops, Mills and CNC's


## Our Students

<article class="grid three-columns" markdown="1">
{% assign ordered-students = site.students | sort: "order-number" %}
{% for student in ordered-students %}
**{{ student.title }}{% if student.grad-year %} '{{ student.grad-year | slice: 2, 2 }}{% endif %}**
<br>{% if student.role %}{{ student.role }}{% endif %}
{% endfor %}

## Our Mentors

<article class="grid two-columns" markdown="1">
{% assign ordered-mentors = site.mentors | sort: "order-number" %}
{% for mentor in ordered-mentors %}
**{{ mentor.title }}**
<br>{% if mentor.role %}{{ mentor.role }}{% endif %}
{% endfor %}
</article>