---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.url %}
  You can find an up to date list of my publications on <u><a href="{{author.url}}">my UCL Profile</a>.</u>
{% endif %}

# {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
