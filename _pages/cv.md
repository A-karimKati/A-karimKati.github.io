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


Internships
======
* Research Internship *(Oct-2022 --> March-2023)*
  * ENCRYPTO group at Technische Universität Darmstadt
  * Host : Prof. Dr. Thomas Schneider 

Grants
======
* **2022**
  * Student Travel Grant by the International Association for Cryptologic Research to attend *AsiaCrypt'22*.
  * Student Travel Grant by the International Association for Cryptologic Research to attend *Real World Crypto Symposium'23*.
* **Oct-2019**
  * PhD Grant at Mohammed VI Polytechnic University, Morocco (Over 4 years).
* **Oct-2018**
  * Grant to undertake a predoctoral research fellowship of 1 year at Mohammed VI Polytechnic University, Morocco.


Publications
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


