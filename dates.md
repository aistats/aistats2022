---
layout: default 
title: Key Dates
weight: 1
---


## {{ site.conference.short_name }} {{ site.conference.year }} Key Dates 


{% for deadline in site.conference.deadlines %} {{ deadline.name }} | {% if deadline.text %}{{ deadline.text }}{% elsif deadline.time %}<time datetime="{{ deadline.time }}">{{ deadline.time | date: "%A, %-d %B %Y %H:%M" }}{% if site.TZ %} ({{ site.TZ }}){% endif %}</time>{% elsif deadline.date %}<time datetime="{{ deadline.date }}">{{ deadline.date | date: "%A, %B %-d, %Y" }}</time>{% endif %}
{% endfor %}

The deadlines are firm. We realize the pandemic is making lives difficult, so
we ask the authors to factor in any uncertainties when preparing their papers.


All submission deadlines are at 12:00 UTC. 
Please refer to [UTC Time Zone Converter](https://www.utctime.net/utc-time-zone-converter)

