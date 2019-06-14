---
layout: home
title: Home
landing-title: 'Some Art by Pete Ashton'
description: null
image: null
author: null
---

{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}