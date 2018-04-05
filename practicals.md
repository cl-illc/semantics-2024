---
layout: lecture
title: Practicals
menu: yes
---
*Spring 2018*

# Practicals

{% assign practicals = (site.data.2018.practicals | where: "selected", "y") %}
{% for practical in practicals %}
{% include assignment.html lecture=practical %}
{% endfor %}


