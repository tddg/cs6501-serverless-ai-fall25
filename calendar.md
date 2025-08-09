---
layout: page
title: Calendar
description: The weekly event calendar.
nav_order: 4
---

# Weekly Calendar

{% for schedule in site.calendar %}
{{ schedule }}
{% endfor %}

