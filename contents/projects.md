---
layout: archive
title: "Projects"
permalink: /projects/
---

{% assign sortedProjects = site.projects | sort: 'date' | reverse %}

{% for post in sortedProjects %}
  {% include archive-single.html %}
{% endfor %}
