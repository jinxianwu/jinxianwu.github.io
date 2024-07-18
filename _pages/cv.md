---
layout: archive
title: "More about me"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* Ph.D in Beijing Institute of Technology, Beijing, China, 2026 (expected)
* M.Eng. in Beijing Institute of Technology, Beijing, China, 2022
* B.Eng. in Qingdao University, Shandong, China, 2019

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
  
Honors & Awards
======
* Best Paper Award of CAC 2021 (Top 1%), Chinese Association of Automation, 2021
* Outstanding Master Student (Top 1%), Beijing Institute of Technology, 2021
* Outstanding Graduates (Top 1%), Beijing Institute of Technology, 2022
