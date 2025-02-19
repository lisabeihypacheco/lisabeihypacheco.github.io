---
layout: page
permalink: /research/
title:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">
      <h2>job market paper</h2>
      {% bibliography -f papers -q @*[type=jmp] %}
</div>

<div class="publications">
     <h2>working papers</h2>
     {% bibliography -f papers -q @*[type=wp] %}
</div>

<div class="publications">
     <h2>work in progress</h2>
     {% bibliography -f papers -q @*[type=wip] %}
</div>
