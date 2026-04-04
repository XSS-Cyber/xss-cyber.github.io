---
layout: default
title: XS's personal space
---

# To feel, to think, to express.

I decided long ago, never to walk in anyones' shadows.

## Notes
<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <small> ({{ post.date | date: "%Y-%m-%d" }})</small>
  </li>
{% endfor %}
</ul>
