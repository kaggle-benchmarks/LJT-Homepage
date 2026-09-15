---
layout: archive
title: "Publications"
permalist: /publications/
author_profile: true
---

{% if site.publications %}
  {% for post in site.publications %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
