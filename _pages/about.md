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

Our research group at the [Department of Food Science & Technology, University of Georgia](https://foodscience.caes.uga.edu/) 
is actively seeking motivated graduate students for both M.S. and Ph.D. programs. 
Selected students can anticipate receiving a research assistantship, 
along with specialized training and hands-on experience 
in the development of sustainable, nutritional, and affordable next-generation foods. 
A general background and interest in food science or related fields such as Chemistry, Biology, or Physics 
are essential for prospective candidates. 
For further information and application inquiries, 
please directly contact Hualu Zhou via an email (<u>hualuzhou@uga.edu</u>).

<span style="color:blue">Recent News</span>
==============
----------------------

{% for post in site.news limit:10  %}
  <li>
    <a href="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
  </li>
{% endfor %}

