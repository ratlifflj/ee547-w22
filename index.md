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


