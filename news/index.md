---
title: Notícias
nav:
  order: 4
  tooltip: Posts, eventos e mais !
---

# {% include icon.html icon="fa-solid fa-newspaper" %}Notícias
{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
