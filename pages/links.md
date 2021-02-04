---
layout: page
title: Links
description: 沒有鏈接的 blog 是孤獨的
keywords: 友站
comments: true
menu: 鏈接
permalink: /edward.github.io/links/
---

> God made relatives. Thank God we can choose our friends.

<ul>
{% for link in site.data.links %}
  {% if link.src == 'life' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>

> 友站鏈接
