---
layout: page
title: Staff
description: A listing of all the course staff members.
nav_order: 2
---

# Staff

## Office Hours

The time and location of office hours are listed as follows.

Links to join the instructor's office hours are posted in Canvas.


## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

## Teaching Assistant

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
