---
layout: archive
title: "Category: Updates"
permalink: /category/news/
---

{% assign category_posts = site.posts | where: "category", "Updates" %}
{% include post_list.html posts=category_posts %}
