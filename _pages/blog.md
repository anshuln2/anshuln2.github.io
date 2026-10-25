---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

This is my technical blog. I document some empirical investigations, side projects and failed research attempts here, with some bias towards AI-security/privacy-themed research.

{% for post in site.categories.blog %}
  {% include archive-single.html %}
{% endfor %}
