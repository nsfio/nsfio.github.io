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
* Ph.D. student, Linguistics & Cognitive Science, University of Delaware (in progress)
<!-- Add earlier degrees here, e.g.:
* M.S. in X, University Y, 20XX
* B.S. in X, University Y, 20XX -->

Work experience
======
<!-- * Spring 20XX: Job Title
  * Institution
  * Duties included: ...
  * Supervisor: ... -->

Skills
======
<!-- * Skill 1
* Skill 2 -->

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
<!-- * Add service/leadership items here -->
