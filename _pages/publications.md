---
layout: archive
title: <div align="center">Publications </div>
permalink: /publications/
author_profile: true
---

<div align="center">You can also find my articles on <a href="https://scholar.google.com/citations?user=hc4y0ZsAAAAJ&hl=en" target="_blank"><b>my Google Scholar profile.</b></a></div>
<hr size="6" width="100%" color="navy">

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
