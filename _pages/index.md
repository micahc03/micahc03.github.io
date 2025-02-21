---
layout: defaults/page
permalink: index.html
narrow: true
title: Home | Micah C
---

## Welcome!

Welcome to my page!

## What is my "Why"?

big hammer

## What are my goals?

runs away cutely

<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


