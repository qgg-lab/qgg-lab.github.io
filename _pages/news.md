---
title: news archive | Wen Huang Laboratory
layout: pages
permalink: /news.html
active: home
---

<ul>
  {% for news in site.categories.news %}
    <li>
      <a href="{{ site.baseurl }}{{ news.url }}">{{ news.date | date: "%m-%d-%Y" }}: {{ news.title }}</a>
    </li>
  {% endfor %}
</ul>