---
layout: archive
title: "Research"
excerpt: "A collection of all the published research works I've been involved in."
permalink: /research/
author_profile: true
---

{% include base_path %}

I'm interested in research related to real-world applications of machine learning. I'd love to get involved in this some more in the future! To more clearly demonstrate the type of application-focused research I'm interested in, here's a list of my past publications. 

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
