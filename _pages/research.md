---
layout: archive
title: "Research"
excerpt: "A collection of all the published research works I've been involved in."
permalink: /research/
author_profile: true
---

{% include base_path %}

I'm rather interested in research related to real-world applications of machine learning. Although I'm currently not in a research position, I'd love to get involved in this some more in the future, whether it be in an industry or academic setting. 

To more clearly showcase the type of application-focused research fields I'm interested in, here's a list of my past publications. 

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
