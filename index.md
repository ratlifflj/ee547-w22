---
layout: home
title: EE547
nav_exclude: true
seo:
  type: Course
  name: EE/AA 547
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

## EE/AA 547 Linear Systems Theory

**Reminder**: EE/AA 510 is a pre-requisite to this course. If you have not taken it, please email me.

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign instructors = site.staffers | where: 'role', 'Teaching Assistant' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Overview and outcomes
This focus of this course is the use of linearity in systems theory. It provides foundational tools for modeling and control and serves as a prerequisite for more advanced courses in control theory, robotics, and optimization. The class will be mathematically rigorous, and builds upon concepts familiar from linear algebra (510), ordinary differential equations, and feedback control. In addition to analytical results, we will see computational tools and illustrate abstract concepts whenever possible using numerical examples.

By the end of this course, you will be able to:
  - construct and simulate linear control system models for physical phenomena;
  - approximate nonlinear control system models using linear control systems;
  - assess stability, controllability, and observability of linear control systems;
  - design and implement a stabilizing controller + observer for linear systems.

This course website/syllabus is a living document.

