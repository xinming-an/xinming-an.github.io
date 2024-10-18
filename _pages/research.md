---
layout: archive
title: "Researches"
permalink: /researches/
author_profile: true
---


Our research focus on complex and high-dimensional data analysis, with a particular emphasis on its relevance to medical research, especially in the context of adverse posttraumatic neuropsychiatric sequelae (APNS) and perioperative outcomes.  related to APNS.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
