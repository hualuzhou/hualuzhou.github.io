---
layout: archive
permalink: /news/
author_profile: true
---

{% for post in site.news reversed %}
  {% include archive-single.html %}
{% endfor %}
