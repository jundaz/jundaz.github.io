---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}{% unless post.symposium %}
  {% include archive-single.html %}
{% endunless %}{% endfor %}

{% for post in site.publications reversed %}{% if post.symposium %}
  {% include archive-single.html %}
{% endif %}{% endfor %}
