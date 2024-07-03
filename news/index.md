---
title: News
nav:
  order: 4
  tooltip: Lab News
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}News

Lab news, updated every so often

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
