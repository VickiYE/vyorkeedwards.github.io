---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.uri %}
  You can find an up to date list of my publications on <u><a href="{{author.uri}}">my UCL Profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
