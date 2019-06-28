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

<div class="section color-2" id="pub-grid">
  <div class="section-container">

{% for post in site.publications reversed %}
  {% include archive-pdf-link.html %}
{% endfor %}

</div>
</div>
