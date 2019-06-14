---
layout: home
title: Home
landing-title: 'Some Art by Pete Ashton'
description: null
image: null
author: null
---

xxx

{% for post in site.categories['Gallery'] %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}