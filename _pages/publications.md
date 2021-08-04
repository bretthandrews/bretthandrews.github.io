---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

All Publications
================
**[NASA ADS](https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0001-8085-5890&sort=date+desc)**

Selected Publications
=====================
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
