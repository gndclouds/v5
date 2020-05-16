---
layout: book
path: "/how-to-run-a-city-like-amazon-and-other-fables/"
date: "2019-09-09"
title: "how to run a city like amazon and other fables"
author:
tags: ['book', 'design fiction']
excerpt: "A preview of my first post"
image: https://assets.bigcartel.com/product_images/246882893/cover_small_stretch.png?auto=format&fit=max&h=1000&w=1000
---


<!-- <ul>
  {% for notes in site.notes %}
  {% if notes.tags != null %}
  <li>
    <a href="{{ notes.url }}">{{ notes.title }}</a>
    <p>{{notes.content}}</p>
  </li>
  {% endif %}
  {% endfor %}
</ul> -->


<ul>
  {% for notes in site.notes %}
  <li>
    <!-- <a href="{{ notes.url }}">{{ notes.title }}</a> -->
    <p>{{notes.content}}</p>
  </li>
  {% endfor %}
</ul>
