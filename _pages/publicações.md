---
layout: archive
title: "Publicações"
permalink: /publicações/
author_profile: true
---

{% if author.googlescholar %}
  Você pode encontrar meus artigos no <u><a href="{{author.googlescholar}}">meu perfil do Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publicações reversed %}
  {% include archive-single.html %}
{% endfor %}
