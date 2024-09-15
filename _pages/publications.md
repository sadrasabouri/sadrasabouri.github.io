---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find the full list of my articles on Google Scholar profile.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
