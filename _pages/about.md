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

Our research lab focuses on integrating chemistry and food technology to develop next-generation foods and biomaterials, along with sustainable production systems.

<span style="color:blue">Recent News</span>
==============
----------------------

{% assign sorted_news = site.news | sort: 'date' | reverse %}
{% for post in sorted_news limit:10  %}
  <li>
    <a href="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.date | date: "%m/%d/%Y" }} - {{ post.title }}</a>
  </li>
{% endfor %}

