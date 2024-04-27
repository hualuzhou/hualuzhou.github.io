---
layout: single
permalink: /
author_profile: true
title: ""
redirect_from:
  - /about/
  - /about.html
---

<span style="color:blue">The Laboratory of Future Foods</span>
==============
----------------------

This research group is how to use advanced food science and technologies to create the next-generation foods for our community. We am expecting that our lab can make significant contributions to this field.

<span style="color:blue">Recent News</span>
==============
----------------------

{% assign sorted_news = site.news | sort: 'date' | reverse %}
{% for post in sorted_news limit:10  %}
  <li>
    <a href="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
  </li>
{% endfor %}

