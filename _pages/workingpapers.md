---
layout: archive
title: "Working Papers"
permalink: /workingpapers/
author_profile: true
---

You can also find my articles on <u><a href="https://scholar.google.co.uk/citations?user=5JSGP1sAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.workingpapers reversed %}
  {% include archive-single.html %}
{% endfor %}
