---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Job Market Paper
{% for post in site.portfolio reversed %}
  {% include archive-published-paper.html %}
{% endfor %}


## Publications

{% for post in site.publications reversed %}
  {% include archive-published-paper.html %}
{% endfor %}


## Work In Progress

{% for post in site.workinprogress reversed %}
  {% include archive-published-paper.html %}
{% endfor %}


