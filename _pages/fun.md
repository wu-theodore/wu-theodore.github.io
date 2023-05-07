---
layout: archive
title: "My Hobbies"
excerpt: "For fun"
permalink: "/fun/"
author_profile: true
---

FUN STUFF HERE

{% for post in site.fun %}
  {% include archive-single.html %}
{% endfor %}