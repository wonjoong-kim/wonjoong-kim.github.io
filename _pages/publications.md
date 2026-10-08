---
layout: page
permalink: /publications/
title: Publications
description: "* Equal contribution"
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Each section lists the entries of _bibliography/papers.bib that match its query, in file order. -->

<div class="publications">

<div class="pub-nav">
  <a href="#preprints">Preprints</a>
  <a href="#conferences">Conferences</a>
  <a href="#journals">Journals</a>
  <a href="#workshops">Workshops</a>
</div>

<h2 class="category-header" id="preprints">Preprints</h2>

{% bibliography --group_by none --query @unpublished %}

<h2 class="category-header" id="conferences">Conferences</h2>

{% bibliography --group_by none --query @inproceedings[category=Conference] %}

<h2 class="category-header" id="journals">Journals</h2>

{% bibliography --group_by none --query @article %}

<h2 class="category-header" id="workshops">Workshops</h2>

{% bibliography --group_by none --query @inproceedings[category=Workshop] %}

</div>
