---
layout: single
permalink: /
author_profile: true
title: ""
redirect_from:
  - /about/
  - /about.html
---

<span style="color:blue">Welcome to the Zhou's Research Group</span>
==============
----------------------

This research group is how to use advanced food science and technologies to enhance
the food nutrition, safety, and quality, and to create the next-generation foods for
our community. We am expecting that our lab can make significant contributions to this field.

**Open positions**

This group is constantly looking for incoming graduate students (M.S./Ph.D) who will study at
[Department of Food Science & Technolgy, University of Georgia](https://foodscience.caes.uga.edu/).
The students will expect to receive research assistantship and obtain professional research training
and experience in next-generation foods and nutrition.
General background and interest in food science or related (e.g., Chemistry, Biology, and Physics)
is necessary. Please directly contact Hualu Zhou via
(<u>zhouhualu@gmail.com</u> or <u>hualuzhou@hotmail.com</u>) for details.

<span style="color:blue">Recent News</span>
==============
----------------------

{% for post in site.news limit:10  %}
  <li>
    <a href="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
  </li>
{% endfor %}

