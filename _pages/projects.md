---
layout: archive
title: "Projects"
excerpt: "An overview of some interesting technical projects I've had a hand in."
permalink: /projects/
author_profile: true
---

{% include base_path %}
This is a collection of some of the bigger projects that I've worked on over the years. These projects range from academic coursework to personal interests. Each project has given me the opportunity to apply my knowledge through practical skill and showcase my abilities. 

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}

