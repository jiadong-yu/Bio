---
layout: page
permalink: /publications/
title: Publications
description: Journal and conference papers by Jiadong Yu.
nav: true
nav_order: 5
---

<style>
  .pub-intro {
    margin-bottom: 1.2rem;
    color: #505050;
    line-height: 1.8;
  }

  .pub-list {
    list-style: none;
    padding-left: 0;
    margin-top: 1rem;
  }

  .pub-list li {
    margin-bottom: 1rem;
    line-height: 1.7;
  }

  .pub-label {
    display: inline-block;
    min-width: 3.2rem;
    font-weight: 700;
    color: #0f3d91;
  }

  .pub-section {
    margin-top: 2rem;
  }
</style>

<p class="pub-intro">
  For a complete citation profile, please visit my
  <a href="https://scholar.google.com/citations?user=lsj5Wv4AAAAJ" target="_blank" rel="noopener noreferrer">Google Scholar</a>.
</p>

<div class="pub-section">
  <h2>Forthcoming / In Progress</h2>
  {% bibliography --query @unpublished %}
</div>

<div class="publications pub-section">
  <h2>Journal Papers</h2>
  {% bibliography --query @article %}
</div>

<div class="publications pub-section">
  <h2>Conference Papers</h2>
  {% bibliography --query @inproceedings %}
</div>
