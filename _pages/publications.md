---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


This is a partial list. You can find a full list of my publications on my [Google Scholar](https://scholar.google.com/citations?user=eI8QA3wAAAAJ&hl=en) page or by checking my [CV](files/cv.pdf).


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
