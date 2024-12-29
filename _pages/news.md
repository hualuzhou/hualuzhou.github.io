---
layout: archive
permalink: /news/
author_profile: true
title: ""
---

News
====
The following news tracks all exciting moments that happened to this lab and its members.

-------------------------

{% assign grouped_posts = site.news | group_by: "category" %}

{% for group in grouped_posts %}
  <h2>{{ group.name }}</h2> <!-- Displays the category name -->
  <ul>
    {% assign sorted_posts = group.items | sort: "date" | reverse %} <!-- Sort by date and reverse for descending order -->
    {% for post in sorted_posts limit:10 %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%m/%d/%Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}



{% comment %}
{% include base_path %}
{% for post in site.news reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}




