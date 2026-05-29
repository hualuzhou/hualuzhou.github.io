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

{% assign news_categories = "Research Achievements|Student Achievements|Lab Development & Activities" | split: "|" %}

{% for category_name in news_categories %}
  {% assign category_posts = site.news | where: "category", category_name | sort: "date" | reverse %}
  <h2>{{ category_name }}</h2>
  <ul>
    {% for post in category_posts %}
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



