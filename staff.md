---
layout: page
title: Staff / Contact
description: A listing of all the course staff members.
nav_order: 5
---

# Staff

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor1' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}



{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}

{% assign teaching_headtf = site.staffers | where: 'role', 'Head TF' %}
{% assign num_teaching_headtf = teaching_headtf | size %}

{% if num_teaching_assistants != 0 or num_teaching_headtf != 0 %}

## Course Staff
<div class="staffers-grid">
{% for staffer in teaching_headtf %}
{{ staffer }}
{% endfor %}

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
</div>
{% endif %}


## Contact 

For administrative or logistical questions, please e-mail class Helpline at [ac215harvard@gmail.com](mailto:ac215harvard@gmail.com) 

## Office Hours 

(See Ed) 
