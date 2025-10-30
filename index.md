---
layout: single
author_profile: true
permalink: /
---

### Welcome

This is **Jaewon Cheon’s personal website**.  
I am a Master's student in Industrial and Management Engineering at Korea University, advised by Prof. [Pilsung Kang](https://scholar.google.com/citations?user=I2pcWZIAAAAJ).  

My primary research interests are **Efficient Sequence Modeling** and **Test-time Computations**.  

---
### NEWS

* **[10/2025]** Will be attending **EMNLP 2025** to present our paper.
* **[08/2025]** Our paper, "COUNTDOWN: Contextually Sparse Activation Filtering Out Unnecessary Weights in Down Projection," was accepted to **EMNLP 2025**.

---
### Recent Posts

<ul class="post-list" style="list-style-type: none; padding-left: 0;">
{% for post in site.posts limit:5 %}
  <li style="margin-bottom: 1.5em;">
    <a href="{{ post.url | relative_url }}" style="font-size: 1.1em; font-weight: bold;">{{ post.title }}</a>
    <p style="margin: 0.25em 0 0 0; font-size: 0.9em; color: #666;">
      {{ post.date | date: "%B %-d, %Y" }}
    </p>
  </li>
{% endfor %}
</ul>

---