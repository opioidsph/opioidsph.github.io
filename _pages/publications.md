---
layout: archive
title: "Professionals"
permalink: /pros/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

![Crisis](https://i.ibb.co/446KxRp/Illustration-sans-titre-2.jpg)
