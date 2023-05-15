---
layout: default
title: News
permalink: /news/
---

# News

{% for item in site.data.news %}

## {{ item.title }}

{{ item.description }}
Date: {{ item.date }}
{% endfor %}
