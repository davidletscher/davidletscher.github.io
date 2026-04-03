---
layout: page
title: All Posts
permalink: /posts/
---

{% if site.posts.size > 0 %}
<ul class="archive-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%B %-d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
{% else %}
<p>No posts published yet.</p>
{% endif %}
