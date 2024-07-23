---
layout: archive
title: "Publications"
permalink: https://scholar.google.com/citations?user=Zr5gTwYAAAAJ&hl=zh-CN
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{https://scholar.google.com/citations?user=Zr5gTwYAAAAJ&hl=zh-CN}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
