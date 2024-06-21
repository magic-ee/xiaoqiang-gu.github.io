---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Below are selected publications and a full list can be accessed via [Google Scholar](https://scholar.google.com/citations?user=Wu2lsugAAAAJ&hl=en).></a></div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
