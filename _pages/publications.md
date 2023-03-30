---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Education
======
* Ph.D Candidate in Electrical Engineering, MIT, 2025 (expected)
* M.S. in Aeronautics and Astronautics, MIT-WHOI Joint Program, 2021
* B.S. in Engineering, Harvey Mudd College, 2019

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
