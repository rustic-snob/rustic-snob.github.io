---
layout: single
title: "Posts"
permalink: /posts/
author_profile: false
---

You can find all my posts here, sorted by date.

<ul class="post-list" style="list-style-type: none; padding-left: 0;">
{% for post in site.posts %}
  <li style="margin-bottom: 1.5em;">
    <a href="{{ post.url | relative_url }}" style="font-size: 1.1em; font-weight: bold;">{{ post.title }}</a>
    <p style="margin: 0.25em 0 0 0; font-size: 0.9em; color: #666;">
      {{ post.date | date: "%B %-d, %Y" }}
    </p>
  </li>
{% endfor %}
</ul>