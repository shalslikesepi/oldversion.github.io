---
layout: archive
title: <div align="center">Publications </div>
permalink: /publications/
author_profile: true
---
<br/>
You can also find my articles on <a href="https://scholar.google.com/citations?user=hc4y0ZsAAAAJ&hl=en" target="_blank">**my Google Scholar profile**</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
