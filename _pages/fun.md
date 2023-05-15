---
layout: archive
title: "My Hobbies"
excerpt: "A highlight reel of some memorable moments while pursuing my hobbies."
permalink: "/passions/"
author_profile: true
---

This space is reserved for miscellaneous endeavors related to my out-of-work hobbies. I hope this provides a better glimpse of my interests and the activities that I may be up to. 

{% for post in site.passions %}
  {% include archive-single.html %}
{% endfor %}