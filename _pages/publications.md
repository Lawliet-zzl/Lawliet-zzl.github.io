---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Education
======
* B.S. in School of Data and Computer Science, Sun Yat-Sen University, 2016
* M.S. in School of Data and Computer Science, Sun Yat-Sen University, 2018
* Ph.D in School of Compute Science, University of Technology Sydney, 2022

Work experience
======
* 2022-2023: Research Associate, School of Compute Science, University of Technology Sydney
* 2023-current: Postdoctoral Research Fellow, School of Computing, Macquarie University
