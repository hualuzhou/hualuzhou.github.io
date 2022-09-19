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

I am currently a postdoctoral researcher at University of Massachusetts Amherst,
and looking for a faculty position in the Food Science and Technology.
My research interest is how to use advanced food science and technologies to enhance
the food nutrition, safety, and quality, and to create the next-generation foods for
our community. I am expecting that our lab can make significant contributions to this field.


<span style="color:blue">Recent News</span>
==============
----------------------

{% for post in site.news limit:10  %}
  <li>
    <a href="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
  </li>
{% endfor %}

