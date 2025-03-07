---
layout: archive
permalink: /research/
author_profile: true
title: ""
---

Overview
======

My primary research interest focuses on how to utilize advanced scientific and technological
principles to drive
<span style="color: blue;">innovation in future foods and biomaterials, as well as their sustainable production systems.</span>
Our work involves utilizing and developing various food chemistry principles
and techniques to explore their fundamental properties, innovative designs and fabrications, and 
practical applications in the development of desirable next-generation foods that excel in many
aspects, such as sustainablility, health, and cost.
My current research emphasizes utilizing plant-derived materials (e.g., 
<span style="color: blue;">plant proteins</span> and 
<span style="color: blue;">bioactive compounds</span>) to achieve 
these goals in a sustainable and efficient manner.

<img src="/images/future_foods.svg" width='400'/>

**Figure 1**. Various characteristics of future foods.

---

{% assign grouped_posts = site.research | group_by: "category" %}

{% for group in grouped_posts %}
  <h2>{{ group.name }}</h2> <!-- Displays the category name -->
  <ul>
    {% for post in group.items %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

{% comment %}
{% include base_path %}
{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}

