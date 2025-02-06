---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Computer Science, Rice University, 2022
* B.S. in Computer Science, Virginia Tech, 2021

Work experience
======
* Summer 2020: Undergraduate Research Assistant
  * Virginia Tech
  * Duties included: Tagging issues
  * Supervisor: Dr. Hoda Eldardiry

* Spring 2020: Undergraduate Research Assistant
  * Virginia Tech
  * Duties included: Tagging issues
  * Supervisor: Dr. Yunhui Zhu
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
