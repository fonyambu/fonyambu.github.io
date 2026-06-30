---
layout: archive
title: "Blog"
permalink: /year-archive/
author_profile: true
---

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

{% if site.posts.size == 0 %}
*Coming soon. Check back for writing on genomics, bioentrepreneurship, and building scientific capacity in East Africa.*
{% endif %}
