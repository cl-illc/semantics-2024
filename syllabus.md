---
layout: photolist
title: Syllabus
menu: yes
---

*Spring 2020*


# Lectures

{% assign lectures = (site.data.2018.lectures | where: "selected", "y") %}
{% for lecture in lectures %}
{% include lecture.html lecture=lecture %}
{% endfor %}


