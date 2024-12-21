---
layout: single
permalink: /
author_profile: true
title: ""
redirect_from:
  - /about/
  - /about.html
---

<span style="color:blue">The Laboratory of Future Foods and Biomaterials</span>
==============
----------------------

This research lab is dedicated to leveraging advanced food science and technology to develop next-generation foods and biomaterials, as well as their sustainable production systems. Our goal is to foster innovation and sustainability for the benefit of our community, and we strive to make significant contributions to this field.

<span style="color:blue">Recent News</span>
==============
----------------------

{% assign sorted_news = site.news | sort: 'date' | reverse %}
{% for post in sorted_news limit:10  %}
  <li>
    <a href="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    <span> - {{ post.date | date: "%m/%d/%Y" }}</span>
  </li>
{% endfor %}

