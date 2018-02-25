---
layout: post
title:  "The Lego Journey Begins"
date:   2018-02-25 14:35:16 -0500
categories: jekyll update
---
Today I purchased 17 pounds of LEGO parts.

{% for image in site.static_files %}
  {% if image.path contains 'assets/images/lego' %}
    <img src="{{ image.path }}" alt="">
  {% endif %}
{% endfor %}