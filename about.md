---
title: About
position: 0
hero-img-url: "/uploads/82b35809f3ee40e6aeb4f90dde5c5cf3.jpeg"
hero-title: We Are Team 5962 <br>perSEVERE
layout: default-with-hero
---

## Our Story and Mission

In April 2015, two engineers from Analog Devices approached Dracut High School to explore the possibility of starting an FRC team as part of the school's Robotics Club. Despite initial hopes and months of effort from many people, the school was, unfortunately, unable to support a FRC team.

Undeterred, 5 students and 4 mentors opened Team 5962 to anyone from the area, rather than only students at a single high school. We approached the University of Massachusetts Lowell, and the College of Engineering graciously offered the use of its Makerspace.

We broadened our recruiting efforts, and by kickoff day our rookie season, our team included 33 students from 8 towns and 8 schools, 12 mentors, and more than 30 sponsors. Since then, we've competed at local district and off-season events, New England District Championships, and the *FIRST* Championship in Detroit.

**Our mission is to foster a vibrant, fun, and collaborative environment that inspires students to explore STEM, solve problems, and develop 21st century skills. We've earned the Chairman's Award at the district and regional level for our dedication to spreading *FIRST* in our communities.**

With our parent organization, Merrimack Valley Robotics, we extend that mission to students K-12 in northeastern Massachusetts, southern New Hampshire, and beyond. For more information about our parent organization Merrimack Valley Robotics, please visit [mvrobtics.net](http://mvrobotics.net)
<div class="divider"></div>

## Our Home

We meet at the UMass Lowell Makerspace (Falmouth 102) a few times a week. This space is graciously offered to us by the Francis College of Engineering. We have access to 3D printers, laser cutters, power tools, laptops, mills, and CNCs.

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
{% if student.image %}<br><img src="{{ student.image }}">{% endif %}
</p>
{% endfor %}
</article>

<div class="divider"></div>

## Our 2026 Graduates

Our graduating seniors have played an essential role in shaping Team Persevere through their dedication, leadership, and commitment to excellence. Over the years, they have contributed countless hours to designing, building, programming, and refining our robots while fostering a culture of collaboration, innovation, and perseverance. Their willingness to mentor younger members, overcome challenges, and represent our team with integrity has left a lasting impact that extends far beyond competition. As they begin the next chapter of their journey, we sincerely thank them for their hard work, passion, and the legacy they leave behind. We are proud to call them members of Team Persevere and wish them continued success in all of their future endeavors.
<article class="grid three-columns">
{% assign ordered-2026-graduates = site.2026-graduates | sort: "order-number" %}
{% for 2026-graduate in ordered-2026-graduates %}
<p>
<b>{{ 2026-graduate.title }}{% if 2026-graduate.grad-year %} '{{ 2026-graduate.grad-year | slice: 2, 2 }}{% endif %}</b>
{% if 2026-graduate.role %}<br>{{ 2026-graduate.role }}{% endif %}
{% if 2026-graduate.school %}<br>{{ 2026-graduate.school }}{% endif %}
{% if student.2026-graduate %}<br><img src="{{ 2026-graduate.image }}">{% endif %}
{% if 2026-graduate.collage %}<br>{{ 2026-graduate.collage }}{% endif %}
</p>
{% endfor %}
</article>

<div class="divider"></div>

## Our Adult Coaches

Team Coaches work for businesses in the area, are parents of team members, and are students at UMass Lowell, where the team meets. The Coaches are all volunteers, offering hundreds of hours (or more) of service each year to help the team out.
<article class="grid two-columns">
{% assign ordered-coaches = site.coaches | sort: "order-number" %}
{% for coach in ordered-coaches %}
<p>
<b>{{ coach.title }}</b>
{% if coach.role %}<br>{{ coach.role }}{% endif %}
{% if coach.image %}<br><img src="{{ coach.image }}">{% endif %}
</p>
{% endfor %}
</article>

## Our Adult Volunteers

Adult Volunteers help the students on the team advance their knowledge on what topics we utilize while working, such as: mechanics, electrical, coding, CAD, business, community outreach, and many more. The Adult Volunteers are here to guide the students, and share their knowledge with everybody.
<article class="grid two-columns">
{% assign ordered-volunteers = site.volunteers | sort: "order-number" %}
{% for volunteers in ordered-volunteers %}
<p>
<b>{{ volunteers.title }}</b>
{% if volunteers.role %}<br>{{ volunteers.role }}{% endif %}
{% if volunteers.image %}<br><img src="{{ volunteers.image }}">{% endif %}
</p>
{% endfor %}
</article>

<div class="divider"></div>