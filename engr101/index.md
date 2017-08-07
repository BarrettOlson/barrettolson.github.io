---
layout: default
title: ENGR 101
---

## Engeerings 101: Introduction to Computers & Programming

Welcome! I will post notes and any slides from Lab here each week. 

- [Course Drive](/404)
- [Course Calender](/404)

### Notes:

<ul class="notes">
	{% for note in site.notes %}
	  <li><span>{{ note.date | date_to_string }}</span> - <a href="{{ note.url }}" title="{{ note.title }}">{{ note.title }}</a></li>
	{% endfor %}
</ul>
