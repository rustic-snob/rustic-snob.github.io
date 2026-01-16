---
title: Welcome!
layout: single
author_profile: true
permalink: /
classes: wide
---

This is **Jaewon Cheon’s personal website**.  
I am a Master's student in Industrial and Management Engineering at Korea University, advised by Prof. [Pilsung Kang](https://scholar.google.com/citations?user=I2pcWZIAAAAJ).  

My primary research interests are **Efficient Sequence Modeling** and **Test-time Computations**.  

---
### NEWS

* **[01/2026]** I will be joining **NAVER Cloud** as a **Foundation Model Research Intern**.
* **[10/2025]** I Will be attending **EMNLP 2025** to present our paper.
* **[08/2025]** Our paper, "COUNTDOWN: Contextually Sparse Activation Filtering Out Unnecessary Weights in Down Projection," was accepted to **EMNLP 2025**.

---
### Seminar

<div style="display: grid; grid-template-columns: repeat(4, minmax(0, 1fr)); gap: 12px;">
  <div>
    <a href="https://www.youtube.com/watch?v=JjxBNBzDbNk" target="_blank" rel="noopener noreferrer" style="display: block;">
      <img src="https://img.youtube.com/vi/JjxBNBzDbNk/hqdefault.jpg" alt="Mamba" style="width: 100%; height: auto; display: block; border-radius: 6px;">
    </a>
    <div style="margin-top: 6px; font-size: 0.9em;">Mamba</div>
  </div>
  <div>
    <a href="https://www.youtube.com/watch?v=Vh7oRJEWXSI" target="_blank" rel="noopener noreferrer" style="display: block;">
      <img src="https://img.youtube.com/vi/Vh7oRJEWXSI/hqdefault.jpg" alt="Medusa" style="width: 100%; height: auto; display: block; border-radius: 6px;">
    </a>
    <div style="margin-top: 6px; font-size: 0.9em;">Medusa</div>
  </div>
  <div>
    <a href="https://www.youtube.com/watch?v=ktpbVgQKy0g" target="_blank" rel="noopener noreferrer" style="display: block;">
      <img src="https://img.youtube.com/vi/ktpbVgQKy0g/hqdefault.jpg" alt="Flash Attention" style="width: 100%; height: auto; display: block; border-radius: 6px;">
    </a>
    <div style="margin-top: 6px; font-size: 0.9em;">Flash Attention</div>
  </div>
  <div>
    <a href="https://www.youtube.com/watch?v=cfIIBBDeZ-0" target="_blank" rel="noopener noreferrer" style="display: block;">
      <img src="https://img.youtube.com/vi/cfIIBBDeZ-0/hqdefault.jpg" alt="BitLLM" style="width: 100%; height: auto; display: block; border-radius: 6px;">
    </a>
    <div style="margin-top: 6px; font-size: 0.9em;">BitLLM</div>
  </div>
  <div>
    <a href="https://www.youtube.com/watch?v=H9fImqBiRl0" target="_blank" rel="noopener noreferrer" style="display: block;">
      <img src="https://img.youtube.com/vi/H9fImqBiRl0/hqdefault.jpg" alt="KAN" style="width: 100%; height: auto; display: block; border-radius: 6px;">
    </a>
    <div style="margin-top: 6px; font-size: 0.9em;">KAN</div>
  </div>
  <div>
    <a href="https://www.youtube.com/watch?v=jjwkjYEbejk" target="_blank" rel="noopener noreferrer" style="display: block;">
      <img src="https://img.youtube.com/vi/jjwkjYEbejk/hqdefault.jpg" alt="Byte Latent Transformer" style="width: 100%; height: auto; display: block; border-radius: 6px;">
    </a>
    <div style="margin-top: 6px; font-size: 0.9em;">Byte Latent Transformer</div>
  </div>
  <div>
    <a href="https://www.youtube.com/watch?v=l7fn8gEUjG4" target="_blank" rel="noopener noreferrer" style="display: block;">
      <img src="https://img.youtube.com/vi/l7fn8gEUjG4/hqdefault.jpg" alt="DeepSeek-R1/V3" style="width: 100%; height: auto; display: block; border-radius: 6px;">
    </a>
    <div style="margin-top: 6px; font-size: 0.9em;">DeepSeek-R1/V3</div>
  </div>
  <div>
    <a href="https://www.youtube.com/watch?v=4pNugYLtECM" target="_blank" rel="noopener noreferrer" style="display: block;">
      <img src="https://img.youtube.com/vi/4pNugYLtECM/hqdefault.jpg" alt="FLA, TTT, Titans, ..." style="width: 100%; height: auto; display: block; border-radius: 6px;">
    </a>
    <div style="margin-top: 6px; font-size: 0.9em;">FLA, TTT, Titans, ...</div>
  </div>
</div>

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
