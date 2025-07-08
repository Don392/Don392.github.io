---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- These works provide an overview of my research.

(* indicates the corresponding author, ¹ indicates the co-first authors.) -->

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
