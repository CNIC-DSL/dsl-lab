---
title: "CNIC DSL - Home"
layout: gridlay
excerpt: "CNIC DSL - Home"
sitemap: false
permalink: /publications/
---


# 发表论文

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
