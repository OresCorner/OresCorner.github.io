
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-J233VX6GNM"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-J233VX6GNM');
</script>

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
* Bachelors of Science in Computer Science, University of Houston, 2026 (expected)

Work experience
======
* Spring 2024: Student Web Developer
  * University of Houston
  * Duties includes: Editing University websites using local CMS
  * Supervisor: The Users
  
Skills
======
* HTML
* CSS
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Javascript

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
