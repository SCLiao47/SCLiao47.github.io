---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% include base_path %}

{% if author.googlescholar %}
  You can find my articles on <a href="{{author.googlescholar}}">my Google Scholar profile</a>.
{% endif %}

(Under construction ... You can find my articles on <a href="https://scholar.google.com/citations?user=bvu9q8wAAAAJ">my Google Scholar profile</a> for now.)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
