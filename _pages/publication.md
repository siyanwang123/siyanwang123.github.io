---
layout: archive
title: "Education"
permalink: /education/
author_profile: true
---

Master in Statistics and data scinece at [UW-Madison](https://www.wisc.edu/)

Bachelor in Information and Computing Science at [Huazhong Agriculture University](https://www.hzau.edu.cn/)

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
