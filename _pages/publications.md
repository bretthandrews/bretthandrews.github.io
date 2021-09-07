---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

## NASA ADS Publication Lists
**[All Publications](https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0001-8085-5890&sort=date+desc)**

**[Refereed First Author Publications](https://ui.adsabs.harvard.edu/search/filter_property_fq_property=AND&filter_property_fq_property=property%3A%22refereed%22&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq=%7B!type%3Daqp%20v%3D%24fq_property%7D&fq_database=(database%3Aastronomy)&fq_property=(property%3A%22refereed%22)&q=orcid%3A0000-0001-8085-5890%20%20author%3A%22%5Eandrews%2C%20b%22&sort=date%20desc%2C%20bibcode%20desc&p_=0)**

## Selected Publications
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
