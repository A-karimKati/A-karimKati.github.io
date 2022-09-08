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
* **Oct 2019 - Present** - PhD Program on Information Technologies and Communications *(Mohammed VI Polytechnic University, Morocco)*
* **Oct 2018 - Oct 2019** - Predoctoral Research Fellowship *(Mohammed VI Polytechnic University, Morocco)*
* **Sept 2016 - Jul 2018** - MSc in Business Intelligence *(Sultan Moulay Slimane University, Morocco)*
* **Sept 2013 - Jul 2016** - BSc in Electronics and Electrical Engineering *(Sultan Moulay Slimane University, Morocco)*
* **Sept 2011 - Jul 2013** - Preparatory Classes to Higher Engineering Schools *(Technical school Med 5, Morocco)*


Work experience
======
* Fall 2022: Research Internship
  * ENCRYPTO group at Technische Universität Darmstadt
  * Supervisor: Prof. Dr. Thomas Schneider 

<!--
Journal Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.type == 'journal' %}
      {% include archive-single-kati.html %}
    {% endif %}
  {% endfor %}</ul>
-->
Conference Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.type == 'conference' %}
      {% include archive-single-kati.html %}
    {% endif %}
  {% endfor %}</ul>
  
Talks
======
<ul>{% for post in site.publications reversed %}
  {% if post.type == 'tutorial' %}
    <li>{% include archive-single-talk-kati.html %}</li>
  {% endif %}
{% endfor %}</ul>

PhD Thesis
======
<ul>{% for post in site.talks reversed %}
  {% if post.type == 'thesis' %}
    {% include archive-single-kati.html %}
  {% endif %}
{% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
    {% include archive-single-teaching-kati.html %}
  {% endfor %}</ul>