---
layout: archive
title: "News"
permalink: /news/
author_profile: false
hero_image: berkeley.jpg
---

{% comment %}
  Each news item is a file in the _news folder (title, date, image, label, summary).
  The list below is built from those files automatically, newest first.
{% endcomment %}
{% assign items = site.news | sort: "date" | reverse %}
<div class="news-timeline">
{% for n in items %}
  <article class="news-item">
    <div class="news-item__date">{{ n.date | date: "%b %Y" }}</div>
    <div class="news-item__media"><a href="{{ n.url | relative_url }}">{% include news-thumb.html item=n %}</a></div>
    <div class="news-item__body">
      <h3 class="news-item__title"><a href="{{ n.url | relative_url }}">{{ n.title }}</a></h3>
      <p>{{ n.summary }}</p>
      <a class="news-item__more" href="{{ n.url | relative_url }}">Read more →</a>
    </div>
  </article>
{% endfor %}
</div>
