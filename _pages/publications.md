---
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

You can also find my articles on my [Google Scholar](https://scholar.google.com/citations?user=GiwTbZIAAAAJ&hl=en).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
