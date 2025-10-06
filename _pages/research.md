---
layout: archive
permalink: /research/
author_profile: true
title: ""
---

Overview
======

Our research work involves utilizing and developing various <span style="color: blue;">food chemistry principles
and techniques</span> to explore their fundamental properties, innovative designs and fabrications, and 
practical applications in the development of desirable next-generation foods that excel in many
aspects, such as <span style="color: blue;">sustainablility, health, and cost</span>.
My current research emphasizes utilizing plant-derived materials (e.g., 
<span style="color: blue;">plant proteins/polysaccharides</span> and 
<span style="color: blue;">bioactive compounds</span>) to achieve 
these goals in a sustainable and efficient manner.

<img src="/images/future_foods.svg" width='400'/>

**Figure 1**. Various characteristics of future foods.

---

{% assign grouped_posts = site.research | group_by: "category" %}

{% for group in grouped_posts %}
  <h2>{{ group.name }}</h2> <!-- Displays the category name -->
  <ul>
    {% assign sorted_posts = group.items | sort: "date" | reverse %}
    {% for post in sorted_posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

