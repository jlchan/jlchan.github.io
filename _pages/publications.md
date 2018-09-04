---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my publications on my 
<a href = scholar.google.com/citations?user=nA29Z5YAAAAJ&hl=en>Google Scholar page</a> 
or on arXiv (under Jesse Chan).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
