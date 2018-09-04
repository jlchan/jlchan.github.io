---
layout: archive
title: "Selected talks"
permalink: /talks/
author_profile: true
---

{% comment %} 
<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>
{% endcomment %}

These are slides for selected recent talks. A complete list of talks can be found on my [**CV**](../files/jcv.pdf).

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
