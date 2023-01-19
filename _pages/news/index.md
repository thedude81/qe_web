---
layout: single
classes: collection
title: "News Archive"
permalink: /news/index
author_profile: false
toc: true
toc_label: "Content"
toc_icon: "cog"  # corresponding Font Awesome icon name (without fa prefix)
show_date: true
---

Last Update: {{ "now" | date: "%d.%m.%Y %H:%M" }}
{: .small}

<ul>
  {% for pages in site.news %}
    <li>
      <a href="{{ pages.url }}">{{ pages.title }}</a>
    </li>
  {% endfor %}
</ul>

