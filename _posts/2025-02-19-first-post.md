---
layout: default
title: First post!
date: 2025-02-19
image: /assets/img/default.png
permalink: /blog/first_post/
short-info: Viktor something something
---
<main class="fade-in">

  <div class="article-hero" style="background-image: url('{{ page.image | default: "/assets/img/default.png" | relative_url }}');">
  </div>

  <section class="article-meta">
    <div class="meta-left">
      <p>Written by Leo</p>
      <p>Published on {{ page.date | date: "%B %d, %Y" }}</p>
    </div>
    <div class="meta-right">
      <a href="#" class="social-btn">X</a>
      <a href="#" class="social-btn">FB</a>
    </div>
  </section>

  <hr>

  <section class="article-body">
    Jag har säkert gjort jättemånga fel, men jag är otroligt nöjd med mig själv över det här
  </section>
</main>