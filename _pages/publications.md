---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find my articles on my <u><a href="{{author.googlescholar}}">Google Scholar</a></u> profile.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
