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
* B.S. in Computer Science, San Jose State University

Work experience
======
* 2022: Software Engineer
  * VMware
  * Built a software tool for offline debugging and triaging, significantly enhancing engineer productivity.

* 2021: Software Development Engineer
  * Amazon Web Services
  * Reduced data center management time by 150% by implementing a backend service for forecasting scenarios.
  * Supervisor: Professor Hub

* 2020: Coding Teacher
  * Computer Science
 
* 2019: Math Teaching Assistant
  * Calculus
  
Skills
======
* Software Development
* Machine Learning Research

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
