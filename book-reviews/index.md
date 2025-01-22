---
layout: default
title: Book Reviews
permalink: /book-reviews/
---

# Book Reviews

Here are all my book reviews:

<ul>
  {% for post in site.categories.book-reviews %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %-d, %Y" }}
    </li>
  {% endfor %}
</ul>